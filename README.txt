Please see the image File_Structure.PNG to see how the TDX_Task file should be structured. Please note packages_part1 and packages_part2 need to be extracted into one packages folder.

I had some issues with SQL when trying to complete this task but tried to work around this. Please find included in this zip file the following: 

-2 .csv files: Customer (Primary key of PersonID) and Sales Header (Primary Key of Transaction GUID and a foreign key of PersonID)

-TDX web app solution that contains 3 web forms. The first web form will lead to either the view part of the task or the import part of the task.  
 
-The Import web form was going to get the user to input a .csv file which would have been read into a datatable, confirm whether the transaction GUID is a GUID and if not either reject the records or reject the entire file. I was also going to implement a feature where the user would be able to manually enter a sale, by entering the PersonID and transaction value. This would generate a GUID and fill in the other values such as First Name and Last Name by getting the information from the customer table.

-The view web form was going to get the user to select a transaction GUID and it would bring back the First Name, Last Name and transaction value. I was also going to get the user to be able to select the person ID and return the total of all the sales transaction values.

I had planned a lot more for this project, some examples would have been: reporting on customers and a user login which would require a username and password. The password would have to be encrypted too.

The contents in the .csv all have headers which were going to be field names in the database.
