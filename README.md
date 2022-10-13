# Data-Cleansing-and-Integration

## TASK 1 AND 2: Data parsing and Cleansing
**NOTEBOOK file**: Data Parsing and Cleansing.ipynb

1. Focuses on  parsing a large XML dataset into a pandas dataframea and examining the resultant structure. 
2. Exploring the iterative techniques and procedures required to wrangle and therefore clean a large data set with unknown data quality issues. In order to work through this data in a more controlled and organised manner I decided to analyse potential data anomalies one column and at a time. 

**INPUTS**:
- Dataset1.xml    

**OUTPUTS**:
- errorlist.csv: list of all changes made to the dataset 
- dataset1_cleaned.csv: Cleaned data output in csv formatt 

## TASK 3: Data Intgegration

**NOTEBOOK file**: Data Integration.ipynb

The objective of this task (Task 3) is to combine the data outputted from task 2 and successfully intergrate at both the schema and data level with data obtained from www.jobhuntlisting.com (dataset 2). To do so the schema of the task 2 dataset will be adopted as the global schema. 


**INPUTS**:
- dataset1_cleaned.csv
- dataset2.csv

**OUTPUTS**:
- dataset_integrated.csv: fully intergrated csv containing dataset 1 & 2 data without duplicates and errors
