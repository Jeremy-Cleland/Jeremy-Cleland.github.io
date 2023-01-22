# Class 11 Reading Notes | MongoDB and Mongoose

## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

Fill in the chart below with five differences between SQL and NoSQL databases:

## SQL NoSQL

- Q: Fill in the chart below with five differences between SQL and NoSQL databases:

  - A:

    - 1. SQL databases are primarily called as Relational Databases (RDBMS); whereas NoSQL database are primarily called as non-relational or distributed database.

    - 2. SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores.

    - 3. SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on collection of documents.

    - 4. For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries

    - 5. For the type of data to be stored: SQL databases are not best fit for hierarchical data storage. But, NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.

---

- Q: What kind of data is a good fit for an SQL database?

  - A: SQL databases are good fit for the complex query intensive environment.

- Q: Give a real world example.

  - A: A:MySQL database

- Q: What kind of data is a good fit a NoSQL database?

  - A: NoSQL database are highly preferred for large data set (i.e for big data).

- Q: Give a real world example.

  - A: Hbase

- Q: Which type of database is best for hierarchical data storage?

  - A: NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.

- Q: Which type of database is best for scalability?

  - A: , SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

- Q: Give a real world example.

- MongoDB

SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

## sql vs nosql (Video)[sql vs nosq](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

- Q: What does SQL stand for?

  - A: Structured Query Language

- Q: What is a relational database?

  - A: A relational database is a type of database that stores and provides access to data points that are related to one another.

- Q: What type of structure does a relational database work with?

  - A: Logical data structures

- Q: What is a ‘schema’?

  - A: A database schema defines how data is organized within a relational database; this is inclusive of logical constraints such as, table names, fields, data types, and the relationships between these entities.

- Q: What is a NoSQL database?

  - A: NoSQL databases (aka "not only SQL") are non-tabular databases and store data differently than relational tables.

- Q: How does it work?

  - A: NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.^[MongoDB](https://www.mongodb.com/nosql-explained)

- Q: What is inside of a MongoDB database?

  - A: Documents and Collections

- Q: Which is more flexible - SQL or MongoDB? and why.

  - A: While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

- Q: What is the disadvantage of a NoSQL database?

  - A: They don't support ACID (atomicity, consistency, isolation, durability

### Bookmark and Review

[mongoose api](https://mongoosejs.com/docs/api.html#Model)
[React Router](https://reactrouter.com/web/api/BrowserRouter)

### Things I want to know more about
