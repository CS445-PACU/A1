# A1

You must produce the E-R diagram in UMLet.  You can edit A1_Create.sql and A1_Queries.sql in dbeaver or in Geany.

* The ER Diagram in: A1_ER.uxf
* The SQL Create Table statements in: A1_Create.sql
* The SQL Statements in: A1_Queries.sql
* A full copy of the database produced by mysqldump in A1_Full.sql

To produce the *A1_Full.sql* file, run the following command in Terminator in your project directory.
```
mysqldump -u PUNetID -p -e --create-options --databases PUNetID_a1 > A1_Full.sql
```

Your database must be created in *PUNetID_a1* on your VM. 
