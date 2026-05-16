# Academic Performance Insights

## Project Name
**Academic Performance Insights**

## Project Overview
Academic Performance Insights is a Python-based data analysis project that generates and analyzes student academic records to understand performance patterns. The project creates a student dataset with roll numbers, names, gender, and marks in Mathematics, Physics, and Chemistry, then performs data preparation, transformation, visualization, and summary reporting.

The notebook first generates a dataset containing **50 student records** with a mix of unique entries, duplicate records, and a few missing values. After that, the data is loaded into Pandas and used for filtering, cleaning-related analysis, calculated fields such as total marks and percentage, grade classification, and visual reports.

## Tech Stack
- **Python**
- **Pandas** for data handling and analysis
- **NumPy** for numerical operations
- **Matplotlib** for data visualization
- **Jupyter Notebook** for development and execution
- **CSV** for dataset storage

## Features in the Project
- Generates a student dataset with:
  - Roll number
  - Name
  - Gender
  - Maths marks
  - Physics marks
  - Chemistry marks
- Includes a mix of:
  - Unique records
  - Duplicate records
  - Records with missing values
- Loads and explores the dataset using Pandas
- Filters students based on gender and name patterns
- Removes duplicate records for cleaner analysis
- Calculates:
  - **Total Marks**
  - **Percentage**
  - **Grade**
- Assigns grades based on percentage:
  - **A** for 80%–100%
  - **B** for 60%–79%
  - **C** for 40%–59%
  - **FAIL** for below 40%
- Creates visualizations such as:
  - Bar chart for average performance of male vs female students
  - Pie chart for pass vs fail ratio
  - Bar chart for subject-wise gender performance
  - Pie chart for grade distribution
- Generates summary reports for:
  - Gender-based average marks
  - Subject-wise descriptive statistics

## Role in this Project
I developed this project independently on my own. My role included:
- Designing the project idea and workflow
- Creating and structuring the dataset
- Performing data preparation and transformation
- Writing the analysis logic in Python
- Building the visualizations and summary reports
- Testing the notebook and verifying the output

## Screenshots of Different Web Pages in the Project

**PERCENTAGE OF MALES vs FEMALES**
![PERCENTAGE OF MALES vs FEMALES](screenshots\perc_males_females.png)

**Percentage of Passed VS Failed Students**
![Percentage of Passed VS Failed Students](screenshots\perc_pass_fail_sts.png)

**Average Marks based on Gender**
![Average Marks based on Gender](screenshots\avg_marks_gender.png)