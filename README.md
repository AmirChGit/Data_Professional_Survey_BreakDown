# Data Professionals Survey Analysis

## Objective
This project aims to work with a real-world dataset collected from a survey of data professionals. It utilizes Power BI to transform and visualize the raw data, providing insights into the data professional landscape. The focus is on practical data cleaning techniques within Power BI, highlighting the challenges and limitations of working with unrefined data.

## Table of Contents
1. Introduction
2. Data Cleaning Techniques
   - Handling "Other" Options
   - Cleaning Salary Range Data
3. Visualizations
   - Overview Visualizations
   - Salary Analysis by Job Title
   - Programming Language Preferences
   - Location Impact on Salary
   - Work-Life Balance and Salary Satisfaction
   - Gender Salary Comparison
   - Data Science Entry Difficulty
4. Dashboard Customization
5. Conclusion
6. Future Work

## 1. Introduction
The dataset includes information such as job titles, salary ranges, programming language preferences, job satisfaction, and demographics. While acknowledging the extensive data cleaning required for a more thorough analysis, this tutorial emphasizes the use of Power BI for simplifying the data and creating basic visualizations.

## 2. Data Cleaning Techniques

### Handling "Other" Options
One of the main challenges addressed is the presence of "other" options in multiple-choice questions, leading to a large number of unique responses. The tutorial introduces a technique of splitting columns based on delimiters (parentheses and colons) to create a simplified "other" category. This approach allows for a more manageable number of options for visualization purposes.

### Cleaning Salary Range Data
Another data cleaning challenge arises from the salary range data, represented as a text string with a dash and a "K" indicating thousands. The tutorial demonstrates a method of splitting the salary range into two separate columns, followed by calculating the average salary. While acknowledging the limitations of this approach, it emphasizes the ability to convert the text data into a numerical representation for visualization purposes.

### Extracting Numerical Values
It illustrates how to split columns based on digit-to-non-digit delimiters, enabling the extraction of numerical values from text strings. This technique is applied to clean up the salary range data by removing characters like "K" and "-" to arrive at usable numerical values.

## 3. Visualizations

  ![image](https://github.com/user-attachments/assets/f571646b-cd07-4c12-ac43-9e9415ec3966)

