# DataAnalystPortfolioProjects
See below for examples of work done in Excel, Power Pivot, Power Query, Python, Power BI, SQL, Data Analysis, Data Visualization, Data Modeling, Hypothesis Testing.

### Data Visualization  
##### Power BI  
This report was built using Power BI and has several tables in the data model utilizing relationships and measures to calculate moving averages. This report is filterable by department. I have implemented several such reports for various departments and use cases and have used a gateway to set up a periodic automatic refresh of the data.    
![image](https://user-images.githubusercontent.com/68308182/209892716-f62e0f0d-9f2c-4367-b678-6519a04a643f.png)

#### Excel  
This report was created using a Power Pivot data model joining several tables with relationships and individual pivot tables for each displayed chart. I have created, maintained, and distributed several dozen excel reports with this method.  
![image](https://user-images.githubusercontent.com/68308182/211935245-ca30989b-2e5f-4b00-9a6c-9d3c4228e316.png)

#### (Python) - Work in Progress - Stay Tuned  

### Data Analysis  
(Python) - Work in Progress - Stay Tuned  
(Excel) - Work in Progress - Stay Tuned  

## Data Modeling  
#### Power BI    
  
#### Building relationships between tables  
![image](https://user-images.githubusercontent.com/68308182/209892886-fb932ea6-cd07-4666-a552-ef434aea25e6.png)  
  
#### DAX formula for calculating a moving average using a date table and relationship  
![image](https://user-images.githubusercontent.com/68308182/209893226-1447efed-c2ac-4c18-8707-2f753deddb0c.png)  



#### Excel Power Pivot  
Building relationships between tables  
![image](https://user-images.githubusercontent.com/68308182/211897509-5ca9d6d5-03e9-4466-bd88-6985119accfc.png)
  
#### Using columns from another table for calculated column (this is comparable to doing a vlookup or a SQL join)  
![image](https://user-images.githubusercontent.com/68308182/211897789-a75b368b-7f54-474a-896c-3cfca251a2fc.png)


## SQL  
Work in Progress - Stay Tuned  

## Power Query  
Work in Progress - Stay Tuned  

## Python  
(data transformation) - Work in Progress - Stay Tuned  


## Excel Formulas and Pivot Tables  

### Vlookup in Excel  
![image](https://user-images.githubusercontent.com/68308182/209589595-bc4042ed-06cf-459f-b38f-5296ca723f95.png)  

### Index Match in Excel  
![image](https://user-images.githubusercontent.com/68308182/209590000-abb79309-e855-4248-a88f-9711a0ef00a0.png)  
  
### Common Math Formulas in Excel  
![image](https://user-images.githubusercontent.com/68308182/210663621-eec3e725-aafb-485a-b21a-24391c65b109.png)
  
### More Advanced Formulas in Excel  
![image](https://user-images.githubusercontent.com/68308182/210662426-6fa27d67-915f-4d00-95f0-81af2bb1d43e.png)
  
### Another Advanced Formula in Excel  
This example showcases one of the more complex excel formulas that i've created which creates the ID for a project work breakdown structure using only one input for the step "level" while referencing the previous ID to find which value to assign. This is especially useful for when you need to add new items which requires rows to be inserted and has the ID update automatically. This is a project management tool.  
![image](https://user-images.githubusercontent.com/68308182/210662853-8b18b8fb-f3a2-4047-a13f-55e95df19020.png)

### Pivot Table  
Simple pivot table showing total, maximum, and average of the sales column for each sales rep and manager with a date slicer for easily filtering to different date ranges. 
![image](https://user-images.githubusercontent.com/68308182/211168002-0b80fae7-66c2-4965-86f0-ddc8acb68311.png)

### Excel Paginated Report + Data Validation + Advanced Formula  
Output of print to pdf for filled out form   
![image](https://user-images.githubusercontent.com/68308182/212389698-19a5a8ce-bd8e-4b3c-a4b1-b947a48693af.png)
  
This form uses data validation from other tables to create drop down lists  
![image](https://user-images.githubusercontent.com/68308182/212389860-230cb4d5-9e29-4562-9f61-361fa35c1f79.png)
  
The drop down data validation references the other drop down menu to reduce the number of options the user has to select from for convenience  
![image](https://user-images.githubusercontent.com/68308182/212391562-ed914561-77cf-4181-b756-035c3a6c1df3.png)

  
The data validation ranges are referenced indirectly where the indirect reference is itself a formula that "builds" the range to reference based on a combination of formulas.  
![image](https://user-images.githubusercontent.com/68308182/212390318-10f40cff-6c70-4c76-bf86-b76a9608ec5f.png)

