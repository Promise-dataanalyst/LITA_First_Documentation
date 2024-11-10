# LITA_First_Documentation
This is where I want to document some of my first Data Analysis activities with the Incubator Hub

# COURSE: DATA ANALYSIS

---

### OVERVIEW
- Data Analysis involves examing, cleaning transforming, 
- and modeling data to discover useful information,
- draw conclusions, and support decision-making.
- The purose of data analysis is to help make informed decisions.



### Project Title: Sales Analysis
---
### Project Overview
---
The objective of this Data Analysis project is to generate insight into sales performamnce of the 

### Data Sources 
- The Data sources here is the Excel sheet or Sales.csv 
- and this is an open source that can be freely downnloaded
- from an open sources such as Kaggle or  FRED or any other suite

### TOOLS USED
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data cleaning,
  2. For Analysis and
  3. For Data Visualization
     
- SQL-Structured Query Language  [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
  1. For Quering of Data
  2. 
- GitHub                  [Download Here](https://www.github.com)
  1. For Portfolio Building
  2. For Documentation
 
 
  ### Data Cleaning and Preparations
  Data cleaning and preparation are being perform in the following ways
  1. Data loading and Inspection
  2. Handling missing variables
  3. Data Cleaning and Formating
  ---   
  ### Exploratory Data Analysis
  EDA involves exploring of Data to answer some questions about the Data such
  - What is the overall sales trend ?
  - Which Product are the top sellers
  - What are the products on the peak sale?
    I included some lines of queries used in the Data Analysis Expression (DAX)
  
  
````
= Table.AddColumn(#"Changed Type2", "Age Sort", each if [CF_age band] = "Under 25" 
````

This data set is an open data from the Incubator Tutor. I cleaned the data by removing duplicates and analyzed data using  Pivot table.

![Capture](https://github.com/user-attachments/assets/7b823a50-c0f4-4e3c-8bbe-a0c7628a59ce)

![Capture 1](https://github.com/user-attachments/assets/74d7a241-3dc6-4345-b6e5-edbf94a7ecd3)


![Capture 2](https://github.com/user-attachments/assets/5192eef6-190b-4727-9e41-efec4770d338)


![Capture 3](https://github.com/user-attachments/assets/d2178fe6-3176-4bb3-b36d-da0ff1479af1)

![Capture 4](https://github.com/user-attachments/assets/c374ffa0-3f13-4db0-a3d5-0af59660d9d5)

![Capture 5](https://github.com/user-attachments/assets/e6a9561c-6beb-4a03-8a5d-65d9685b4e66)

![Capture 6](https://github.com/user-attachments/assets/fecb8908-222c-46da-80bb-edc4aeb6d19c)

![Capture 7](https://github.com/user-attachments/assets/d1f349ad-aa27-4555-8edf-cb383f0a8c90)

![Capture 8](https://github.com/user-attachments/assets/0325d57f-5449-40ed-9561-c29c3e3cc1e7)

I extracted the first and Lastname from the Email addresses using functions in Excel 
**To get First name**
````
=LEFT(B6, FIND(".",B6)-1)
````
**To get Surname**
```` 
=MID(B6,FIND(".",B6)+1,FIND("@",B6)-1-FIND(".",B6))
 `````
![Capture 9](https://github.com/user-attachments/assets/7b6c9bb2-4767-44fd-99b9-a39040d7409c)


**Use Concatenate to join words together example to join first and Surname together with space in between to get Full name**

````
=CONCATENATE(B6, " ", C6)
````

![Capture 10](https://github.com/user-attachments/assets/69e38868-c5a3-4734-a660-35927eb7e96f)

**Used Map for States and Country**

![Capture 13](https://github.com/user-attachments/assets/8448ecf9-24b1-44f4-a96e-daf0e8b2873f)


 **Used functions to clean dataset appropriately on excel**
 ```
=Upper
=Lower
=Proper
=Proper(Trim)  
````
![Screenshot (123)](https://github.com/user-attachments/assets/357bed06-d243-479f-98fb-124ca1243b69)


![Screenshot (124)](https://github.com/user-attachments/assets/de3170ca-2af2-42d1-8d25-6f3913941e50)



