# Power-BI-Project_HR_Analytics

#Objective:
Help an organization to improve employee performance and improve employee retension i.e reduce attrition by creating a HR Analytics dashboard

#Solution:
To make a Dashboard

#Procedures
Step 1:- 
Determining KPI(Key Performance Indicators) which we obtain by analysing and uderstanding the problem and its objective.

Step 2:-
Finding the trends which are relevant for the project
For this we use Pivot Table
(However if using a csv file note that you cannot make pivots as it doesnt allow multiple sheets)

So using Pivot Tables
We obtain some trends which makes sense according to the project.

Step 3:- 
DATA CLEANING AND PROCESSING
We use PowerQuery of Power BI for this
Transform Data

1. Finding Void Entries
> Home > Column Quality
![Image description](Data_Transformation/missing.png)
> Ordering the column in assending order 
> we get all the null values at the top 
![Image description](Data_Transformation/assending.png)
>Now removing top rows by Remove Rows > Remove Top Rows
![Image description](Data_Transformation/Remove TopRows.png)

2. Finding Dupplicates
> Removing Duplicate values 
> Group by > Grouping by distinct value
![Image description](Data_Transformation/duplicates.png)
>Filter will show 2
![Image description](Data_Transformation/dupl.png)
>Selecting all the columns and removing the duplicates
![Image description](Data_Transformation/duplicate all remove.png)

3. Correcting Misc Errors
> Misc Case : We replace the error 
![Image description](Data_Transformation/misc.png)
> Data Type Correction by Detect Data Type
![Image description](Data_Transformation/data type.png)


4. Creating Dashboard
> HR_Analytics_Dashboard
![Image description](Data_Transformation/Dashboard.png)

> HR_Analytics_Dashboard for Human Resource Department 
![Image description](Data_Transformation/HumanResource.png)

> HR_Analytics_Dashboard for Research and Development 
![Image description](Data_Transformation/R&D.png)

> HR_Analytics_Dashboard for Sales
![Image description](Data_Transformation/Sales.png)

