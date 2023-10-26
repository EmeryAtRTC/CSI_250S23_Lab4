<div align="center">  
    <img src="Images/logo.jpg" alt="Logo">
    <h2>Renton Technical College</h2>
    <h3>CSI-244</h3>
</div>
<br>

# Lab4 Database Access

## Purpose - The goal of this assignment is to develop your understanding of:
 - Database creation and access in .NET
 - The Code first technique for connecting a database and a .NET Project.
 - Entity Framework

## Outcomes - By creating this assignment, you will be able to:
 - Create a database using C# code.
 - Connect the database to your project using Entity Framework.
 - Run queries on the database using LINQ methods and Entity Framework.

# Instructions

## Task 1: Clone this repository to your local machine and open the included .Net 6 MVC project

## Task 2: Create the following Models representing an auto repair shop. Choose the datatypes for the properties that you think would be the best fit. (20pts)
 - Customer.cs
    - Id
    - FirstName
    - LastName
    - Phone
- Vehicle.cs
    - Id
    - Make
    - Model
    - Year
    - Mileage
    - VIN
 - ServicePerformed.cs
    - Id
    - TimePerformed
    - Notes
 - Technician.cs
    - Id
    - FirstName
    - LastName
    - EmployeeNumber

## Task 3: Using C# code establish the following relationships between the models (You will need to add more properties to the models beyond of what is listed above to accomplish this) (10pts)
 - A Customer can have many Vehicles.
 - A Vehicle can only have one Customer.
 - A Vehicle can have many Services Performed.
 - A Service is performed by one technician.
 - A technician can have many Services Performed.

## Task 4: Generate the database from these models

## Task 5: Create a CustomerController and implement CRUD functionality with corresponding Views for the Customer table. (10pts)

## Task 6: Generate a database diagram in SSMS and include a screenshot of the DB diagram with your submission. (Take the screenshot and save it in the folder for the repository before you create your final commit) (10pts)

## Task 7: Create a commit with a comment of "Submission for Lab4" and push the changes to the repository.


Feel free to message your instructor or the TA on Canvas if you have any questions.
