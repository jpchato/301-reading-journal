# Database Normalization 
* Intro to Database Normalization
  * Process to organize databases into tables and columns
  * Tables should be about specific topics
* Reasons for Database Normalization
  * Minimize duplicate data
  * Minimize or avoid data modification issues
  * simplify queries
* Data Duplication and Modification Anomalies
  * 2 problems from data duplication
    * Increases storage and decreases performance
    * Becomes more difficult to maintain data changes
  * Insert Anomaly
    * There are facts we cannot record until we know information for the entire row
  * Update Anomaly
    * Same info in several rows. If all rows are not updated then inconsistencies appear.
  * Deletion Anomaly
    * Deletion of a row causes removal of more than one set of facts
* Search and Sort Issues
  * database normaliztion can make searching and sorting easier
* Definition of Database Normalization
  * First normal form- The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns
  * Second normal form- The table is in first normal form and all the columns depend on the table's primary key
  * Third normal form- the table is in second normal form and all of its columns are not transitively dependent on the primary key