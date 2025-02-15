# Python-Activity
# Employee Data Analysis

## Overview
This project reads and analyzes employee data from a CSV file (`emp_data_v2.csv`). The script performs various calculations, such as:
- Printing the CSV file content
- Calculating the average salary
- Finding the highest salary
- Counting the number of employees per department
- Identifying the employee with the highest salary
- Writing the processed results into a new file (`results.txt`)

## Features
- Reads employee data from a CSV file
- Calculates and prints:
  - Average salary
  - Highest salary
  - Number of employees in each department
  - Name of the employee with the highest salary
- Saves the results into `results.txt`

## Prerequisites
Ensure you have Python installed (version 3.x recommended). No additional dependencies are required.

## File Structure
```
📂 Employee-Data-Analysis
│-- emp_data_v2.csv      # Input data file
│-- results.txt          # Output file with computed results
│-- script.py            # Python script for analysis
│-- README.md            # Project documentation
```

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/nandana-0646/Employee-Data-Analysis.git
   cd Employee-Data-Analysis
   ```
2. Place your `emp_data_v2.csv` file in the project directory.
3. Run the script:
   ```sh
   python script.py
   ```
4. View the results in the terminal and in `results.txt`.

## Sample CSV Format
Ensure your CSV file follows this structure:
```csv
id,name,department,salary
1,John Doe,Engineering,75000
2,Jane Smith,HR,65000
3,Emily Davis,Marketing,72000
```

## Expected Output
Example terminal output:
```
Average Salary: $70666.67
Highest Salary: $75000
Number of Employees in Each Department:
Engineering: 1 employees
HR: 1 employees
Marketing: 1 employees
Employee with Highest Salary: John Doe
Results written to results.txt
```

## License
This project is licensed under the MIT License.

## Author
Nandana S Madhu(https://github.com/nandana-0646)

