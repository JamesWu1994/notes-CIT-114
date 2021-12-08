# 10.01 What is a Database?
* A database is a shared collection of related data used to support the activities of a particular organization.
* A database has the following properties:
  * It is a representation of some aspect of the real world or a collection of data elements (facts) representing real-world information.
  * A database is logical, coherent and internally consistent.
  * A database is designed, built and populated with data for a specific purpose.
  * Each data item is stored in a field.
  * A combination of fields makes up a table. For example, each field in an employee table contains data about an individual employee.
* A database management system (DBMS) is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.
 * data elements: facts that represent real-world information
 * database: a shared collection of related data used to support the activities of a particular organization
 * database management system (DBMS): a collection of programs that enables users to create and maintain databases and control all access to them
 * table: a combination of fields

# 10.02 Characteristics and Benefits of a Database
* The processing power of a database allows it to manipulate the data it houses, so it can:

 * Sort
 * Match
 * Link
 * Aggregate
 * Skip fields
 * Calculate
 * Arrange

* Because of the versatility of databases, we find them powering all sorts of projects. A database can be linked to:

 * A website that is capturing registered users
 * A client-tracking application for social service organizations
 * A medical record system for a health care facility
 * Your personal address book in your email client
 * A collection of word-processed documents
 * A system that issues airline reservations

* A database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database.
* concurrency control strategies: features of a database that allow several users access to the same data item at the same time
* data type: determines the sort of data permitted in a field, for example numbers only
* data uniqueness: ensures that no duplicates are entered
* database constraint: a restriction that determines what is allowed to be entered or edited in a table
* metadata: defines and describes the data and relationships between tables in the database
* read and write privileges: the ability to both read and modify a file
* read-only access: the ability to read a file but not make changes
* self-describing: a database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database
* view: a subset of the database

# 10.03 Relational Databases
* A relation, also known as a table or file, is a subset of the Cartesian product of a list of domains characterized by a name. And within a table, each row represents a group of related data values. A row, or record, is also known as a tuple. The columns in a table is a field and is also referred to as an attribute. You can also think of it this way: an attribute is used to define the record and a record contains a set of attributes.
* The principal storage units are called columns or fields or attributes. These house the basic components of data into which your content can be broken down.

# 10.04 Non-relational Databases
* In the year 1970’s when relational database came into picture, data schema to be worked upon were reasonably elemental and simple wherein the data items were to be arranged as a set of formally described tables with rows and columns. But with the need to store volumes and variety of data (unstructured) in recent years, non-relational database technologies have emerged to address the requirement that allow data to be grouped together more naturally and logically.
* NoSQL is an approach to databases that represents a shift away from traditional relational database management systems (RDBMS). To define NoSQL, it is helpful to start by describing SQL, which is a query language used by RDBMS. Relational databases rely on tables, columns, rows, or schemas to organize and retrieve data. In contrast, NoSQL databases do not rely on these structures and use more flexible data models. NoSQL can mean “not SQL” or “not only SQL.” As RDBMS have increasingly failed to meet the performance, scalability, and flexibility needs that next-generation, data-intensive applications require, NoSQL databases have been adopted by mainstream enterprises. NoSQL is particularly useful for storing unstructured data, which is growing far more rapidly than structured data and does not fit the relational schemas of RDBMS. Common types of unstructured data include: user and session data; chat, messaging, and log data; time series data such as IoT and device data; and large objects such as video and images.
