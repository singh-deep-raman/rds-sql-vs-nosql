# rds-sql-vs-nosql

In this repository, we will learn how to chose database for your project, like whether SQL or NoSQL database fits for your needs.

# REASONS TO GO FOR SQL DATABASE
* If your schema is defined i.e. your schema doesn't change frequently, go for SQL Database
* SQL databases are only Vertically Scalable using more CPU/RAM/SSD
* If you want to save your data as rows/columns of tables, go for SQL database
* SQL databases are good for transactional data

# REASONS TO GO FOR NO-SQL DATABASE
* If your schemas are dynamic, rapidly changing or unstructured, then go for NoSQL database
* NoSQL databases are Horizontally Scalable using Sharding or more nodes
* If you want to save your data as Document or Key-Value or Graph or Wide-column stores, then go for NoSQL Database
* Benefits of NoSQL database
... * You can create documents without defining their structure
... * Each document can have it's own unique structure
... * You can add fields as you go


# Some important points related to Databases
* MySQL database can be replicated across multiple nodes
* While SHARDING can't be done on most SQL databases, it can be done on MY-SQL database
* ORACLE is a professional, expensive database suitable for enterprise companies with large data needs
* PostgreSQL is a hybrid SQL/NoSQL database systems.
... * It is ORDBMS (Object Oriented Relational Database Management System)
... * It has highest ACID compliance of all SQL databases
* Cassandra benefits from "Masterless Design" means all of it's nodes are identical
* Due to "Masterless Design" of Cassandra, users can read and write from all Casssandra nodes.
* Cassandra's WRITE and READ are very fast where as UPDATE and DELETE are very slow in terms of performance
* Cassandra also avoids single point of failure
