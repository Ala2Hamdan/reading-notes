# Normalization
![image](https://blog.knoldus.com/wp-content/uploads/2020/03/normal-forms-1.png)
- Database normalization
is a process used to organize a database into tables where every table should be has the specific topic and the supporting topics included to reduce the number of duplicate data within database. 
 

- why we need Database normalization ?
 1. to minimize duplicate data.
 2. to minimize or avoid data modification issues.
 3. to simplify queries.

 * There are three modification anomalies 
- Insert Anomaly
- Update Anomaly
- Deletion Anomaly

* You can eliminate or reduce these anomalies by separating the data intodifferent tables.
* This puts the data into tables serving a single purpose.
![image](https://learn.saylor.org/pluginfile.php/1401085/mod_page/content/2/normalization_process.jpg)
* There are three common forms of database normalization: 
1. First Normal Form (1NF) : 
 The rules 
- Each table cell should contain a single value.
- Each record needs to be unique.
2. Second Normal Form (2NF) 
The rules
- Be in 1NF
- Single Column Primary Key
3. Third Normal Form (3NF) 
The rules
- Be in 2NF
- Has no transitive functional dependencies

* What is a Primary Key?
- A primary is a single column value used to identify a database record uniquely.
* What is a Foreign Key?
- Foreign Key references the primary key of another Table! It helps connect your Tables.
