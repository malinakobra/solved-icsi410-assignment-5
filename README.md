Download Link: https://assignmentchef.com/product/solved-icsi410-assignment-5
<br>
Write 15 separate SQL DDL or update DML queries, named “Query36” through “Query50”. Each query will contain a SQL DDL or update DML statement that is your solution for the translation of a “plain English” DDL or DML request. Each query is worth one point. The 15 “plain English” queries are:

<ol start="36">

 <li>Create a table, called Dealership2, which has the same column names and data types as the Dealership Do <strong><u>not</u> </strong>include a primary key constraint. Do <strong><u>not</u></strong> include an input mask for the dzip column.</li>

 <li>Create a primary index, called PrimaryKey, on the dcode column in Dealership2 Use “CREATE INDEX…” syntax.</li>

 <li>Create a table, called Vehicle2, which has the same column names and data types as the Vehicle Do <strong><u>not</u> </strong>include a primary key constraint. <strong><u>Do</u></strong> include a foreign key constraint to Dealership2 and name it ForeignKey_to_Dealership2.</li>

 <li>Add a primary key constraint, called PrimaryKey, on the vvin column in Vehicle2.</li>

</ol>

Use “ALTER TABLE…” syntax.

<ol start="40">

 <li>Create an index, called FK_to_Dealership2, on the foreign key column in Vehicle2.</li>

</ol>

Use “CREATE INDEX…” syntax.

<ol start="41">

 <li>Using “INSERT INTO…SELECT” syntax, insert all the rows from Dealership into Dealership2.</li>

 <li>Using “INSERT INTO… VALUES” syntax, insert into the Dealership2 table:</li>

</ol>

193, Asg 5 Test Dealership, 10 Main St, Albany, NY, 12203

<ol start="43">

 <li>Using “INSERT INTO… VALUES” syntax, insert into the Vehicle2 table:</li>

</ol>

A1B2C3WXYZ0123456, 193, 2015, SUBA, sedan, blue, 2310, gas, 6

<ol start="44">

 <li>Change vweight to 3,210 in the row you inserted in Query43, identifying this row by using its primary key value.</li>

 <li>For all Dealership2 rows with a dcity value of “Albany”, change dstate to “GA” and dzip to null.</li>

 <li>Erase the single row of data inserted in Query43. Use the primary key value to pick the right row.</li>

 <li>Remove the foreign key constraint in Vehicle2 which was created by Query38.</li>

 <li>Drop the Vehicle2</li>

 <li>Erase all the data in Dealership2.</li>

 <li>Drop the Dealership2</li>

</ol>