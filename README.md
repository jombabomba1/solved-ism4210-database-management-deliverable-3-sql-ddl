Download Link: https://assignmentchef.com/product/solved-ism4210-database-management-deliverable-3-sql-ddl
<br>



<h1>INSTRUCTIONS</h1>

Please read the description and the requirements of Deliverable #3 carefully before responding. If you have any questions or clarifications, feel free to contact me via email (<u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="2f4e4b465b46425a44474a5d454a4a6f">[email protected]</a> ufl.edu</u>), during my office hours, or by appointment. <strong> </strong>Keep your responses succinct and clear. No additional explanations should be required in addition to your write up to convey your ideas. <strong> </strong>

All submissions should be <u>individual work</u> only. Do not discuss your answers with your class mates or group members. Plagiarism will not be tolerated.

No late submissions will be accepted. If you have trouble submitting assignments to the e-learning system, please contact me <u>before</u> the submission deadline.

<strong><u>Page Limit:</u></strong>  The SQL statements for each table be written on a single page. Your submission should have at least one page per table, and the SQL statements for each table should start on a new page.

<strong><u>Format: </u></strong>  You will submit the SQL statements described below. Copy and paste all the statements and the diagram into a Word documents that you can save and submit as a PDF. See page 3 of this document for an example of how to present the statements.  The name of your file should be <strong>&lt;LastName&gt;_&lt;FirstName&gt;_IP3.pdf. </strong>Submissions that do not follow the formatting guidelines will not be graded. Submissions where the results are not legible will not be graded.

<h1>DELIVERABLE #3 – SQL DDL</h1>

For this deliverable, you will be creating the database for the Hippodrome database in MySQL. The relations for the database have been defined as shown on Page 2. Based on this information, you must complete the following:

<table width="735">

 <tbody>

  <tr>

   <td width="586">Department of Information Systems &amp; Operations Management      Warrington College of Business Administration, University of Florida</td>

   <td width="149"><strong>ISM 4210</strong><strong>  </strong><strong>Database Management</strong> <strong> </strong></td>

  </tr>

  <tr>

   <td width="586"><strong>Individual Project</strong></td>

   <td width="149"> </td>

  </tr>

 </tbody>

</table>




<strong>STEP 1:</strong> Create a new database in MySQL called <strong>TheHipp</strong>.




<strong>STEP 2:</strong>  Create all the tables as follows:

<ul>

 <li>Write the CREATE statements for the table corresponding to each of the relations. You must decide which data types (and field size, when applicable) will be appropriate for each column in each table.  Each table must have a Primary Key and the appropriate Foreign keys (if applicable)</li>

 <li>Write at least <u>two</u> ALTER statements to either add columns or Primary Key or Foreign Key constraints to any of the tables.</li>

 <li>Execute all the CREATE and ALTER statements in MySQL.</li>

 <li>Use the DESC commmand to describe each table and include the results as shown in the attached template.       List all the relationships in your database using the following</li>

</ul>

SELECT CONSTRAINT_NAME, TABLE_NAME, COLUMN_NAME,

<h2>              REFERENCED_TABLE_NAME, REFERENCED_COLUMN_NAME</h2>

FROM information_schema.KEY_COLUMN_USAGE  WHERE (CONSTRAINT_SCHEMA = ‘TheHipp’) ;

<strong>STEP 3:</strong> Insert data into the tables as follows:

<ol>

 <li>Write <u>one</u> INSERT statement for each of the tables (you may use any dummy data that you can make up)</li>

 <li>Write a select statement for each of the table to display the contents of each table.</li>

 <li>Execute all the INSERT and SELECT statements in MySQL.</li>

</ol>

<strong>NOTE:</strong> You may use the snipping tool or screenshot tool to copy the results from the MySQL Workbench to the Word document.

<table width="735">

 <tbody>

  <tr>

   <td width="586">Department of Information Systems &amp; Operations Management      Warrington College of Business Administration, University of Florida</td>

   <td width="149"><strong>ISM 4210</strong><strong>  </strong><strong>Database Management</strong> <strong> </strong></td>

  </tr>

  <tr>

   <td width="586"><strong>Individual Project</strong></td>

   <td width="149"> </td>

  </tr>

 </tbody>

</table>










<table width="735">

 <tbody>

  <tr>

   <td width="586">Department of Information Systems &amp; Operations Management      Warrington College of Business Administration, University of Florida</td>

   <td width="149"><strong>ISM 4210</strong><strong>  </strong><strong>Database Management</strong> <strong> </strong></td>

  </tr>

  <tr>

   <td width="586"><strong>Individual Project #3 Template</strong></td>

   <td width="149"> </td>

  </tr>

 </tbody>

</table>

For each relation, you must present your results using the following template (a blank word document is available on Canvas).

<table width="667">

 <tbody>

  <tr>

   <td width="667"><strong>RELATION NAME: </strong><strong> </strong></td>

  </tr>

  <tr>

   <td width="667"><strong>CREATE Statement  </strong>CREATE TABLE Customer(CustomerID INT PRIMARY KEY,LastName VARCHAR(30) NOT NULL,FirstName VARCHAR(30));<strong>ALTER Statement (<em>Optional</em>) </strong>  <strong>INSERT statement  </strong>INSERT INTO Customer (CustomerID, LastName, FirstName) VALUES (123456, “Pond”, “Amy”); <strong>SELECT statement </strong>SELECT * FROM Customer;<strong>DESC statement </strong>DESC Customer; </td>

  </tr>

 </tbody>

</table>








