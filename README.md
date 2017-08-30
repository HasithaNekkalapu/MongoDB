# MongoDB

--> Design two document (complex object) schemas corresponding to this data:

1.	The PROJECT document will include the following data: Pnumber, Pname, Dname (of the controlling department), plus a list of the employees that work on the project {employees: Lname, Fname, Hours}.
2.	The DEPARTMENT document will include the following data: Dname, the department manager’s Lname, and a list of the locations of the department {locations: Dlocation}

--> Data files for the EMPLOYEE, DEPARTMENT, WORKS_ON, PROJECT, and DEPT_LOCATIONS tables will be provided.

1.	Install MongoDB on your computer.
2.	Write programs to extract the data needed for the two document types above (PROJECT and DEPARTMENT) from the relational data files, and load these documents into the MongoDB system. Notice that the data from each document will be the result of a join on more than one file. You can load your data in an SQL system, and write a query to extract the data needed for each document in relational format, and then convert the query result from the relational format into JSON for loading on MongoDB
3.	Write some MongoDB queries to retrieve some of the stored documents.

