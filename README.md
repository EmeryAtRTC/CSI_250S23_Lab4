<div align="center">  
    <img src="Images/logo.jpg" alt="Logo">
    <h2>Renton Technical College</h2>
    <h3>CSI-250</h3>
</div>
<br>

# Lab 4 Database Access

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

## Task 2:Create the following Models representing an auto repair shop 
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

## Task 3: Create an Edit action int eh AlbumController with a GET and a POST (8 pts)
 - On Get take in an Id parameter and return a view with a form for editing the Album
    - If no album is found matching the id, return NotFound()
 - On Post take in an Album parameter
    - Use both client and server-side validation to check the information passed to the Album before allowing the edit to go through.
    - If the data in the album is valid locate the corresponding album in the list using the Id and update that album in the list.

## Task 4: Create a functioning search HTML button and HTML input to the Album Index View (8pts)
 - When the button is clicked pass the value to an artistName parameter in the Index endpoint.
 - Filter the Artist Names to match the value passed.
 - If no value is passed the index view should return all of the albums.
     - EXTRA CREDIT - find artists that are similar but not matching. For example, if a minor typo is entered but the rest of the artist is correct then Search should still find the artist. 

## Task 5: Add an HTML Select to the top of the Album Index View (8 pts)
 - The Select should have all of the different DISTINCT prices of the albums.
 - When the user chooses a price pass the selected value to an albumPrice parameter in the Index Endpoint.
 - Filter the album prices to match the value passed.
 - If no value is passed the index view should return all of the albums.

## Task 6: When complete create a commit with the note "Submission for Lab 3" and push the changes to the repository

# Tips for success
- Commit early and often. As you complete each step create a new commit.
- Refer to the example code and the weekly powerpoint
- Office Hours are Mondays and Fridays from 11a-1pm, if you are struggling with any of the assignments please come by.


Feel free to message your instructor or the TA on Canvas if you have any questions.
