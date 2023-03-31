# College-Readiness-Trends
  College Readiness Trends for Schools in Kentucky

---
This project is how Kentucky schools have performed on the College Readiness exam over the years through this project.  However, I have analyzed last 2 years of data only, since the data is not available more than that.

1. List of schools in Kentucky that met with Benchmark.
2. How does the average ACT Composite Score look over the years? By county and by demographic
3. How does the average ACT score for each subject over the years go? By Demographic/County, School
4. What is the percentage of students who met benchmarks over the years? By County and/or By School

The raw data file is from https://www.kyschoolreportcard.com/datasets?year=2022

Datasets: Kenucky school report card.    

Academic Performance:Assessment Results: The ACT



The final data used was also edited from the raw file in the following ways:

1. Removed unnecessary columns from the dataframe 
2. Removed null values found in the dataframes



## Summary

The entire project is in Python using Jupyter Notebooks. The following is a guide to accessing the project files:
1. Fork the repository [repo link](https://github.com/yathridv/College-Readiness-Trends.git)  
2. Clone the repository from your Github account
3. Install the **requirements.txt** file to install necessary packages
4. There are FOUR primary files included in the datasets directory

    Data_act_school.ipynb   ---  Percentage of students who met benchmarks over the years? By County and/or By School
    Data_act_composite.ipynb  ---  ACT Composite Score trending for all demographics by County
    Data_State_act_subject_demographic.ipynb   -- The Average ACT Score Treding for each subject in Kentucky for a specificied demographic.
    Data_County_act_subject_demographic  --  The Average ACT Score Treding for specificied school for each subject by specified demographic and county in Kentucky.
   
    Basically every file is broken out into three sections:
        1. Cleaning the Data
        2. Answering the Questions
        3. Plotting the trends

       
## Features
The following features are included in this analysis:
- **Feature 1: Read Data In**
    - Used pandas to read in data downloaded into a dataframe
- **Feature 2: Manipulate and Clean Data**
    - Clean the dataframe to remove columns not relevant for project hypothesis
    - Remove null values from data set
- **Feature 3: Analyze your data!**
    - Merging the dataframes with a specific join operation
    - Reordering columns
- **Feature 4: Visualize your data!**
    - Made graphs using Matplotlib. Graphs include:
        - Bar Plots
        -
 
