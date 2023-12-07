# Lab 4 - From Relational Schema to Document Databases
This lab will meet the following objectives:

1.  Distinguish the difference between a relational non-relational database schema.

2.  Interpret JavaScript object notation(JSON) data exchange format

## Instructions
For this lab, you will practice converting an ER model into a JSON document store.  

![alt text](https://instructorc.github.io/site/slides/database/images/general/album_artist_erd.PNG)

You will record your relationships within this readme file. 


## Requirements

### Deliverable 1 - Data Definition Language (5 Points)
1 Recreate the database schema identified above.  You can do this one of two ways.  You can use the Modeling tool in Workbench or you can write the SQL commands to create the database and related tables.  Whether you create the database schema using the database modeling tool in MySQL workbench or you create via command line, you will need to provide the commands used to create the database and related tables.  You can include those commands within the file you will use for deliverable 2.  
  1. Make sure all of the relationships are properly configured
  2. Make sure the primary key is specified and auto increments for both the **CLIENT** and **POLICY** table
  3. Make sure all columns in the database are marked as NOT NULL
  4. Enforce that the relationship between **CLIENT** and **POLICY** are strong and enforce cascading if either a **CLIENT** or **POLICY** is deleted.
  5. Include the SQL commands used for creating the database and tables into the file you will use for deliverable 2.


### Deliverable 2 - Data Manipulation Language (10 Points)
Create a file called **lab3.sql** and add the following queries into the file.  You will need to take a screenshot of the rendered output for each command and place a screenshot of your output beneath the example output provided.  Make sure to place a SQL comment above each command identifying the query.  In order to make changes to the data, you may need to change the SQL Editor settings.  You can do this by navigating to EDIT -> SQL Editor -> and unchecking Safe Updates.  It is advised to restart MySQL Workbench after changing this setting.


### Extra Credit (2 Points)
List all clients along with their respective policies.<br>
<img src="https://instructorc.github.io/site/slides/database/images/lab3/ec.PNG" width="550" alt="output query Extra credit"/>



## Submission Guidelines

For this lab, you will submit 2 items to the repository that has been assigned to you.  The two items that you will need to submit are listed below: 
1. The README.MD file that includes screenshots of the result grid window for each SQL query
   1. Include the image beneath the output image I provide

2. The **lab3.sql** file.  The lab3.sql file should be uploaded to your repository

Once you have completed both of the items above, you will need to submit the link to your repository for lab3 prior to the due date and time listed.  Make sure you receive an email confirmation notifying you that the assignment has been submitted.


## Lab Resources
- [W3 Schools SQL tutorial](https://www.w3schools.com/sql/)
- [Make a ReadMe file Web-based Editor](https://www.makeareadme.com/)
- 
