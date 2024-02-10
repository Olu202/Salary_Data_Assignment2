Salary Data Processing
This script is designed to process salary data stored in a CSV file named salary_data.csv. It provides functionalities to retrieve employee details, create dictionaries of employee data, and export employee details to a CSV file within a directory named "Employee Profile".

Usage
The data path is correctly adapted to my environment. Modify the file path in the pd.read_csv() function to point to the location of the salary_data.csv file in the directory.

Execute the script to load the salary data into a pandas DataFrame and define necessary functions for data processing.

Utilize the following functions:

get_employee_details(name)
This function retrieves details of an employee based on the provided name.

Parameters:

name: Employee name to search for.
Returns:

If the employee is found, returns a dictionary containing the details of the employee.
If no employee is found, returns a message indicating that the employee was not found.
export_employee_details(employee_name)
This function exports the details of an employee to a CSV file within a directory named "Employee Profile".

Parameters:

employee_name: Name of the employee whose details are to be exported.
Behavior:

Checks if the employee details exist.
Creates the "Employee Profile" directory if it doesn't exist.
Writes the employee details to a CSV file named details.csv within the "Employee Profile" directory.
Error Handling
The script includes try-except blocks to handle potential errors gracefully. If an error occurs during employee data retrieval or export, an error message is displayed, and the script may return None to indicate failure.

The below is for the readme to R script to Unzip the folder
#Description

This R script unzips a folder containing employee details as a CSV file, loads the data into a DataFrame, and provides options for data exploration and cleanup.

# Key Features

Unzips a specified folder.
Reads CSV data from the unzipped folder.
Displays a summary of the data (optional).
Provides a placeholder for further data exploration or analysis.
Optionally removes the CSV file and unzipped folder after processing.
# Prerequisites

R (version 3.5.0 or later recommended)
unzip package
dplyr package
# Installation

Install required packages using the following command in R:
Code snippet
install.packages(c("unzip", "dplyr"))
Use code with caution. Learn more
# Usage

Adapt file paths:
Modify the paths within the script to match the locations of your zipped folder and desired unpacked folder.
Run the script:
Execute the R script.
Explore or analyze data:
Use the employee_data DataFrame for further analysis or visualizations within the # ... your code here ... section.
# Configuration

No configuration options are currently available.
# Troubleshooting

Verify file paths for accuracy.
Ensure the zipped folder contains a valid CSV file named "details.csv".
If errors occur, refer to the printed error messages for guidance.
