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
