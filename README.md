DATA WRANGLING

Project description: Data wrangling for reports received by the students and employees at UCW.

Project title: data wrangling for resolution of reports at UCW.

Objective: the primary goal of this project is to perform comprehensive data wrangling to prepare a robust dataset for employee violation reports at UCW. By cleaning, transforming, and consolidating data from AWS services, the project aims to enhance the accuracy and usability of reports for subsequent analysis and reporting.

Background: UCW has human resource department, from the last 6 months they are getting reports on violation. They collected the witnesses list as well. Now they start working on that project.

Dataset: the data wrangling process will involve various datasets, including:

o Violation id - it's a unique id to find the reports

o Student id - the student who gave the report

o Name - name of the reporter

o Violation type - what kind of violation is it?

o Date of violation - which day this violation has occurred

o Resolution date - the final resolution day

Methodology:

1- Data collection:

I chose this domain to work on this project. Based on these policies I took some sample datasets.

Https://www.ucanwest.ca/wp-content/uploads/2023/07/ucw-procedure-8001p-respectful-workplace-2023-06-28.pdf

2- Data assessment:

o Conducted an initial assessment of the data quality to identify issues such as missing values, duplicates, and inconsistencies across different datasets by using AWS data brew service in AWS.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b0bbe956-bc38-42b4-bcac-6b1418ccd029">

3- Data cleaning:

<img width="468" alt="image" src="https://github.com/user-attachments/assets/82f3f0ab-d356-4194-bb85-73593ec9b1bd">

o Addressed missing values through appropriate methods and after cleaning part is done, the results are stored back in s3 in transformed bucket (system).

o Remove duplicate records and correct inconsistencies in data by preparing recipes.

4- Data transformation:

<img width="468" alt="image" src="https://github.com/user-attachments/assets/e956e1ee-2c7d-4a77-8981-fa9ed8f5e828">

Perform data type conversions to ensure that all fields are in suitable formats for analysis (e.g., converting strings to datetime objects). Aggregate data as necessary to ensure that it aligns with the intended analysis.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/141f4bac-b3a9-40b7-bbbb-7c8e0004ec62">

Tools and technologies:

o AWS s3 - AWS data brew - AWS glue.

Timeline:

• Expected completion of the project: 10 weeks, including phases for assessment, cleaning, transformation.

This data wrangling project aims to establish a high-quality dataset that enables UCW to conduct effective resolution for the violations, ultimately enhancing strategies, and completely eradicate the violations at workplace or universities.
