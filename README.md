# Capstone-Online-Retail-Customer-Pattern
# 1. Problem Statement:
An online retail store is trying to understand the various customer purchase patterns for their firm, 
you are required to give enough evidence based insights to provide the same.
# 2. Project Objective:
Project objective is to:
 Find useful insights about the customer purchasing history that can be an added 
advantage for the online retailer.
 Segment the customers based on their purchasing behavior.
# 3. Data Description:
 For this project we are using online_retail.csv data that contains 387961 rows and 8 
columns and table given below gives the description of the features present in the data.
![Data Description](https://github.com/Aditibisht13/Capstone-Online-Retail-Customer-Pattern/assets/154453925/bd252160-f7fd-418a-ab6b-4631ca642b8f)
# 4. Data Pre-processing Steps and Inspiration
Following are the steps used for data pre-processing:
 Necessary libraries were imported for EDA of the data such as Pandas, Numpy,
 Matplotlib, Seaborn etc.
 The data csv file was loaded in the jupyter notebook and checked for info.
 Checking if data contains any missing values so that can be dealt before proceeding 
further. The missing data values were dropped for this dataset as their contribution is 
overall data was low.
 The datatype of Customer ID was changed to string as per Business understanding.
 Two more columns are added namely Amount (unit price*quantity) and Type (extracting 
last two words of description to categorize the product)
 Several graphs were plotted to find out top 20 most selling products, Top ten clients,
Country that generated highest revenue etc. Attaching the graphs from the Jupyter 
notebook. The inferences drawn from these graphs will be explained in the Insights drawn 
section.



