# cassandra_modelling

 ***Credits***
Udacity Data Engineer Nanodegree Program

## Rubric

ETL Pipeline Processing

- [ x ] ***Student completes the ETL pipeline procedures***: Student creates event_data_new.csv file.

- [ x ] ***Student uses the correct datatype for each Cassandra CREATE statement***: Student uses the appropriate datatype within the CREATE statement. 

Data Modeling

- [ x ] ***Student creates correct data models for the queries they need to run***: Student creates the correct Apache Cassandra tables for each of the three queries. The CREATE TABLE statement should include the appropriate table. 

- [ x ] ***Student can set up the data model correctly to generate the exact responses posed in the questions***: Student demonstrates good understanding of data modeling by generating correct SELECT statements to generate the result being asked for in the question.
The SELECT statement should NOT use ALLOW FILTERING to generate the results.

- [ x ] ***Student models the data by using appropriate table names.***: Student should use table names that reflect the query and the result it will generate. Table names should include alphanumeric characters and underscores, and table names must start with a letter.

- [ x ] ***Student has given careful thought to how the data is modeled in the table and the sequence and order in which data is partitioned, inserted and retrieved from the table.***: The sequence in which columns appear should reflect how the data is partitioned and the order of the data within the partitions.

PRIMARY KEYS

- [ x ] ***The PRIMARY key for each table should uniquely identify each row in each of the tables.***: The combination of the PARTITION KEY alone or with the addition of CLUSTERING COLUMNS should be used appropriately to uniquely identify each row.

Presentation

- [ x ] ***Student provides responses to the questions***: Scripts have an intuitive, easy-to-follow structure with code separated into logical functions. Naming for variables and functions follows the PEP8 style guidelines.

- [ x ] ***Students notebook code should be clean and modular***: Code should be organized well into the different queries. Any in-line comments that were clearly part of the project instructions should be removed so the notebook provides a professional look.
