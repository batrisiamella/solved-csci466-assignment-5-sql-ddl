Download Link: https://assignmentchef.com/product/solved-csci466-assignment-5-sql-ddl
<br>
For this assignment, you must write an SQL script. An SQL script is a text file that contains a sequence of SQL commands to be run. Yours should include commands for each of the following, in order:

<ol>

 <li>Run a statement that will remove all of the tables that will be created below. This will allow the script to be run again without any errors caused by existing tables.</li>

 <li>Create a table called dogs with a dog id, a breed, and a name. The id of the dog should be the primary key, and should be automatically assigned the next available value when inserting a new row into the table.</li>

 <li>Put <strong>five </strong>rows into the dog table with example data. Make up the data yourself.</li>

 <li>Run the command DESCRIBE dogs;</li>

 <li>Run the command SELECT * FROM dogs;</li>

 <li>Create a table called visits that contains a visit id as primary key (this should take the next available key value when a new row is added). It should also have a foreign key that references a row in the dog table, and an attribute to hold the date that the visit took place.</li>

 <li>Put at least <strong>eight </strong>new rows into the visits Since there are only five dogs, this means that some dogs will have multiple visits.</li>

 <li>Run the command DESCRIBE visits;</li>

 <li>Run the command SELECT * FROM visits;</li>

 <li>Add a column to the visits table to hold the time of the visit.</li>

 <li>Change the value for the newly-added attribute in several of the existing rows. There are several date/time functions available in SQL, and you can choose to use any that are appropriate.</li>

 <li>Run the command SELECT * FROM visits;</li>

</ol>

If a data type is not specified in this document, anything <em>reasonable </em>should be fine. Use your discretion.

You should include comments in the script that identify which commands match which of the requirements.

Comments in SQL are written with a — before them.