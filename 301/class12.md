# Mongo and Mongoose

1. Fill in the chart below with five differences between SQL and NoSQL databases:
> SQL databases are primarily called as Relational Databases (RDBMS); whereas NoSQL database are primarily called as non-relational or distributed database.
> SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores.
> SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
> SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable.
> SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on collection of documents.

2. What kind of data is a good fit for an SQL database?
> SQL databases are good fit for the complex query intensive environment

3. Give a real world example.
> MySQL Community Edition
MySQL database is very popular open-source database. It is generally been stacked with apache and PHP, although it can be also stacked with nginx and server side javascripting using Node js

4. What kind of data is a good fit a NoSQL database?
> NoSQL database are highly preferred for large data set (i.e for big data)

5. Give a real world example.
> MongoDB

6. Which type of database is best for hierarchical data storage?
> NoSQL

7. Which type of database is best for scalability?
> SQL


# sql vs nosql

1. What does SQL stand for?
> Structured Query Language

2. What is a realational database?
> Works with certain assumptions.

3. What type of structure does a relational database work with?
> Logical Data Structure.

4. What is a ‘schema’?
> The term "schema" refers to the organization of data as a blueprint of how the database is constructed

5. What is a NoSQL database?
> NoSQL is a type of database that stores and retrieves data without needing to define its structure first - an alternative to the more rigid relational databases.

6. How does it work?
> Each type of NoSQL database would be designed with a specific customer situation in mind, and there would be technical reasons for how each kind of database would be organized. The simplest type to describe is the document database, in which it would be natural to combine both the basic information and the customer information in one JSON document. In this case, each of the SQL column attributes would be fields and the details of a customer’s record would be the data values associated with each field.

7. What is inside of a Mongo database?
> MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.

8. Which is more flexible - SQL or MongoDB? and why.
> While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

9. What is the disadvantage of a NoSQL database?
> NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability.