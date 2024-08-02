
This Python project involves the creation of a Sales Prediction Model using publicly available data from the US Census Bureau. 

There are important 3 files in this directory:
1. Zohd_Khan_Sales_Prediction.pdf - This is the file of the report associated with this project (all code is still visible in this file).
2. Monthly Sales Prediction.ipynb - This is the source code file. Installation of Jupyter Notebook required to open and run this file.
3. mrtssales92-present.xlsx - This is the source data file. 

**INSTRUCTIONS TO RUN CODE**

1. Download the source data file and the source code file, and place them both into a new folder somewhere in your file explorer
2. Copy the file path for wherever the file is located in your file explorer and assign it to the "file_path" variable in the first code cell. 
3. For the variable "csv_file_path", also in the first cell, you must update the logic for this variable's value to match whatever location you want the new csv files to be stored in, while still keeping the part "{sheet_name}_retail_data.csv" that is at the end.
4. 
   For example, the variable's value should look something like this: f"C:/Users/YourUserName/Desktop/FolderName/{sheet_name}_retail_data.csv"

5. For the variable "csv_file_paths", you can do the same thing as in step 3, but leave the other part of the code "for sheet_name in sheet_names", as well as the square brackets, as is.

  For example, the structure should look something like this: [f"C:/Users/YourUserName/Desktop/FolderName/{sheet_name}_retail_data.csv for sheet_name in sheet_names]

7. After the file path and the additional logic for this particular variables is appropriately adjusted, the rest of the code should run seamlessly. If you encouncter any issues, I apologize sincerely, as I should have made everything more simple. In such an event, the associated pdf file would still be great for reviewing the code and reading the report aspect of the project.

Thank you for taking the time to view my project. 


