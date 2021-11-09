# NoSQL DataBases

## What is NoSQL

The term NoSQL refers to not only SQL or non-relational databases. NoSQL databases are databases that store data in the format other than relational tables.

## Why NoSQL ?

NoSQL DB’s provides mechanism for easy insertion and retrieval of data over traditional SQL Data bases.Traditional SQL is slow when it deals with large amount of data. To resolve this, we need to scale-up our system which is very expensive. Whereas NoSQL database provide “scale-out” feature when the database load is high. Additionally, NoSQL provides more flexibility for big and large amounts of data and for different schemas of the data.

### Features of NoSQL database’s

* Flexible Schemas
* Horizontal Scaling
* Fast queries due to data Model
* Ease of use for Developers.
  
## Types of NoSQL databases

NoSQL databases are classified into 4- types based on schema of data. Each of these databases have its own merits and limitations.
*  Key-value pair databases
*  Document-oriented databases
*  Wide-column databases
*  Graph databases
  
## Key-Value pair Databases

This is the most basic type of NoSQL database. As the name suggests, it is a database where each item is stored in the form of a key-value pair. It is designed in such a way that it handles heavy and large data. It stores data in the form of a hash table where each key is unique and the value can be of any data type. It provides faster access to the data.

![Key-value pair](https://i.stack.imgur.com/nzc2C.png)

This kind of NoSQL database is used as a collection, dictionaries, associative arrays, etc. These databases helps the developer to store schema-less data. They work best for shopping cart contents.

Dynamo, Riak are some NoSQL examples of key-value store DataBases.


## Document-oriented Databases

These database store data in the form of key value pairs. Here the values are stored in the form of a Document. The document is stored either in the format of JSON or XML file.

![Document-Oriented DataBase](https://www.researchgate.net/profile/Andre-Ribeiro-9/publication/288872507/figure/fig4/AS:669111159910404@1536539940239/Example-of-a-documents-oriented-database-for-the-Academic-Management-System.png)

These document-oriented database are mostly used in real-time analytics and e-commerce. 

These databases don’t perform well with multiple queries against varying aggregate structure.

CouchDB,MongoDB are popular Document-oriented database systems.

## Wide- Column store databases

These databases stores data in the tabular format this is very similar to traditional SQL systems. The only difference between them is here we can have a dynamic column data whereas in the traditional system the rows and columns are fixed.

![Wide- Column store](https://www.researchgate.net/profile/Michael-Mior/publication/264859776/figure/fig1/AS:668915290083333@1536493241409/Data-layout-in-wide-column-stores.png)

These are very helpful and effective on aggregation queries like SUM, AVG, MEAN ... etc. as the data is readily available in the columns. 

Column-based NoSQL databases are widely used to manage data warehouse, CRM, Library card catalogs.

HBase and Cassandra are widely used for column-based databases.

## Graph Based NoSQL Databases

These databases store data in the form of nodes and edges. Nodes typically store entities and edges store relations between the entities. In these databases every node and edge have a unique identifier. In relational databases tables are loosely connected whereas in Graph-based databases are multi-relational in nature.

![Graph Based Database](https://dist.neo4j.com/wp-content/uploads/20180814232054/graph-technology-data-model.png)

Graph base database mostly used for social networks, logistics, spatial data.
Neo4J, Infinite Graph are some popular graph-based databases.

## Advantaged of NoSQL Over RDBMS
* It Works well with Big Data.
* No Predefined schema is required. 
* NoSQL handles unstructured data also.
* Cheaper to manage.
* Insertion and retrieval of data is easy.
* Scaling - Scale out / horizontal scaling.

## Disadvantages of NoSQL Databases
* Data Integrity
* Normalization of data
* No ACID Compliance
* It doesn't perform well with relational data.
  
![Comparison](https://miro.medium.com/max/1000/1*1QyI7Zxx73mkG0FcwNUyuw.jpeg)
  
## Summary
* NoSQL databases handles well with Big data.
* It handles structured,semi-structured and un-structured data.
* NoSQL datastores offers horizontal scale at various [CAP Theorem](https://en.wikipedia.org/wiki/CAP_theorem) tradeoffs
* NoSQL databases do not perform fast transactions.
  
## Reference Links
* https://en.wikipedia.org/wiki/CAP_theorem
* https://towardsdatascience.com/datastore-choices-sql-vs-nosql-database-ebec24d56106
* https://www.mongodb.com/nosql-explained/nosql-vs-sql
* https://www.youtube.com/watch?v=xQnIN9bW0og
* https://www.youtube.com/watch?v=uD3p_rZPBUQ
