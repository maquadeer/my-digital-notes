---
{"dg-publish":true,"permalink":"/untitled/dbms-recap/"}
---

- [[Untitled/DBMS RECAP#1. DBMS, ITS PURPOSE AND ADVANTAGES\|1. DBMS, ITS PURPOSE AND ADVANTAGES]]
- [[Untitled/DBMS RECAP#2. Functions of a DBA\|2. Functions of a DBA]]


# Unit 1
### 1. DBMS, ITS PURPOSE AND ADVANTAGES
A Database Management System (DBMS) is software that manages, organizes, and controls access to a database. Its primary purpose is to provide an efficient and structured way to store, retrieve, and manipulate data. Here are the main purposes and advantages of using a DBMS:
**Purposes of a DBMS:**
1. **Data Storage:** DBMSs are used to store data in an organized and structured manner. Data is typically stored in tables, which consist of rows and columns.
2. **Data Retrieval:** DBMSs provide tools and query languages (e.g., SQL) to retrieve specific data from the database. This allows users to search, filter, and extract information easily.
3. **Data Manipulation:** DBMSs support data manipulation operations like adding, updating, and deleting records. This ensures data accuracy and consistency.
4. **Data Security:** DBMSs offer access control mechanisms to regulate who can access, modify, or delete data. This helps protect sensitive information and ensures data integrity.
5. **Concurrency Control:** In multi-user environments, DBMSs manage concurrent access to the database to prevent data conflicts and maintain consistency.
6. **Data Integrity:** DBMSs enforce data integrity constraints, such as unique keys and referential integrity, to maintain the accuracy and consistency of data.
7. **Backup and Recovery:** DBMSs provide mechanisms for data backup and recovery, allowing organizations to safeguard data and restore it in case of data loss or system failures.
8. **Data Abstraction:** DBMSs abstract the physical structure of data from the users, making it easier to work with data without needing to understand the underlying storage details.

**Advantages of Using a DBMS:**

1. **Data Centralization:** DBMSs centralize data storage, reducing data redundancy and ensuring data consistency across the organization.
2. **Data Security:** DBMSs offer robust security features to protect sensitive data through user authentication, authorization, and encryption.
3. **Data Integrity:** By enforcing data integrity constraints, DBMSs maintain the accuracy and reliability of data.
4. **Data Accessibility:** Users can easily access and query the database, promoting data availability and usability.
5. **Concurrency Control:** DBMSs manage multiple users accessing the same data concurrently without causing data corruption or conflicts.
6. **Scalability:** DBMSs are scalable, allowing organizations to handle increasing amounts of data as their needs grow.
7. **Backup and Recovery:** Automatic backup and recovery mechanisms ensure data can be restored in case of accidental data loss or system failures.
8. **Data Independence:** Changes to the database structure (schema) do not typically affect how users interact with the data, promoting data independence.
9. **Data Analysis:** DBMSs often support tools for data analysis and reporting, enabling organizations to gain valuable insights from their data.
10. **Data Consistency:** With transaction management and ACID properties (Atomicity, Consistency, Isolation, Durability), DBMSs ensure data consistency even in the presence of failures.

Here's a tabular comparison differentiating between a Conventional File Processing System and a Database Management System (DBMS) based on various characteristics:

| Characteristic                   | Conventional File Processing System | Database Management System (DBMS) |
|----------------------------------|-------------------------------------|-----------------------------------|
| Data Storage                      | Data is stored in separate files or records with little to no structure. | Data is stored in structured tables with well-defined relationships. |
| Data Redundancy                   | High data redundancy as data may be duplicated across multiple files. | Reduced data redundancy through normalization and centralized storage. |
| Data Integrity                    | Data integrity is often compromised due to limited enforcement of constraints. | Strong enforcement of data integrity constraints (e.g., primary keys, foreign keys). |
| Data Access                       | Data access methods are often program-specific, leading to inconsistent access. | Standardized query languages (e.g., SQL) for consistent and efficient data access. |
| Data Security                     | Limited security features, often reliant on file permissions and access control lists. | Robust security mechanisms, including user authentication and authorization. |
| Data Backup and Recovery          | Manual backup and recovery procedures, often involving file copies. | Automated backup and recovery tools and mechanisms. |
| Scalability                       | Limited scalability as adding new data or modifying the structure can be complex. | Scalable architecture to handle growing data volumes and evolving requirements. |
| Data Independence                 | High coupling between data and applications, making changes to data structure challenging. | Data independence; changes to the database schema do not impact applications. |
| Data Consistency                  | Lacks transaction management; data consistency may be compromised in case of failures. | ACID properties (Atomicity, Consistency, Isolation, Durability) ensure data consistency. |
| Data Analysis and Reporting       | Limited support for data analysis and reporting; often requires custom code. | Built-in tools and features for data analysis, reporting, and business intelligence. |
| Cost and Maintenance              | Lower initial costs but potentially higher maintenance costs due to complexity. | Higher initial costs but lower maintenance costs due to automation and efficiency. |

### 2. Functions of a DBA
some common functions of a DBA include:
1. **Database Installation and Configuration:** DBAs are responsible for installing database management systems (DBMS) and configuring them according to the organization's needs and best practices.
2. **Database Design and Schema Management:** DBAs work with application developers and data analysts to design and maintain the database schema. They define tables, relationships, constraints, and data types to ensure efficient data storage and retrieval.
3. **Data Security:** DBAs implement and enforce security measures to protect the database from unauthorized access, data breaches, and other security threats. This includes user authentication, access control, and encryption.
4. **Data Backup and Recovery:** DBAs establish and maintain backup and recovery procedures to ensure data availability in case of system failures, disasters, or data corruption. They perform regular backups and test recovery processes.
5. **Performance Tuning:** DBAs monitor database performance and identify and resolve performance bottlenecks. This involves optimizing SQL queries, indexing, and configuring database parameters for optimal performance.
6. **Capacity Planning:** DBAs assess the storage and processing needs of the database and plan for its future growth. They ensure that the database can handle increasing data volumes and user loads.
7. **Data Migration and ETL (Extract, Transform, Load):** DBAs manage the process of transferring data from one system to another, often involving data transformation and cleansing. This is crucial when transitioning to a new database platform or integrating data from various sources.
8. **Database Monitoring and Maintenance:** DBAs continuously monitor database health, resource utilization, and error logs. They perform routine maintenance tasks such as index rebuilding, database optimization, and software patching.
9. **Backup and Disaster Recovery Planning:** Developing and maintaining a comprehensive disaster recovery plan that outlines steps to be taken in the event of data loss or system failure.
10. **Troubleshooting and Problem Resolution:** DBAs investigate and resolve database-related issues, including data corruption, performance problems, and application errors.
11. **Disaster Recovery Testing:** Periodically testing the organization's disaster recovery plan to ensure that data can be successfully restored in the event of a catastrophic failure.

### 3. [Three schema arc aka levels of abstraction](https://www.javatpoint.com/dbms-three-schema-architecture)

### 4. [Dbms-Architecture](https://www.javatpoint.com/dbms-architecture)

# *Less Vital Topics*

### 5. Diff DBs and their characs
#### 1. Relational Database
   - **Structured Data:** Relational databases store structured data in tables with predefined schemas, making them suitable for well-organized data.
   - **ACID Compliance:** They adhere to ACID properties (Atomicity, Consistency, Isolation, Durability) to ensure data integrity and transaction reliability.
   - **SQL Query Language:** Relational databases use SQL (Structured Query Language) for data manipulation and retrieval.
   - **Strong Data Integrity:** They enforce data integrity through constraints like primary keys, unique keys, and foreign keys.
   - **Support for Joins:** Relational databases support complex queries and table joins for data analysis.
#### 2. NoSQL Database
   - **Schema Flexibility:** NoSQL databases can store semi-structured or unstructured data, offering schema flexibility.
   - **High Scalability:** Many NoSQL databases are designed for horizontal scalability, making them suitable for handling large volumes of data.
   - **Variety of Data Models:** Different types of NoSQL databases include document stores, key-value stores, column-family stores, and graph databases, each optimized for specific data models.
   - **Eventual Consistency:** Some NoSQL databases may prioritize eventual consistency over strong consistency, which can be suitable for certain applications.
#### 3.Document Database:
   - **Semi-Structured Data:** Document databases store data in semi-structured documents (e.g., JSON or XML) with flexible schemas.
   - **High Read and Write Throughput:** They are often optimized for high read and write throughput, making them suitable for content management and real-time analytics.
   - **Query by Content:** Document databases allow for querying data based on the content of documents.
4. **Key-Value Store:**
   - **Simple Data Model:** Key-value stores offer a simple data model where data is stored as key-value pairs.
   - **High Scalability:** They excel at horizontal scaling and are used in caching, session management, and distributed applications.
   - **Low Latency:** Key-value stores provide low-latency access to data due to their simple structure.
5. **Column-Family Store:**
   - **Columnar Storage:** Data is stored in columnar fashion, making it suitable for analytical workloads.
   - **Scalability:** Column-family stores are highly scalable and often used for big data and time-series data storage.
6. **Graph Database:**
   - **Graph Data Model:** Graph databases are designed for storing and querying data with complex relationships, making them suitable for social networks, recommendation engines, and fraud detection.
   - **Efficient Relationship Queries:** They excel at traversing and querying graph-like structures.
7. **In-Memory Database:**
   - **Data in RAM:** In-memory databases store data in system memory (RAM), providing extremely fast read and write access.
   - **Low Latency:** They are used for applications requiring low-latency data access, such as real-time analytics and caching.
8. **Time-Series Database:**
   - **Time-Ordered Data:** Time-series databases are optimized for handling data with timestamps, making them suitable for IoT data, monitoring, and financial applications.
   - **Efficient Time-Based Queries:** They provide efficient means of querying data based on time intervals.
9. **Spatial Database:**
   - **Geospatial Data:** Spatial databases are designed to store and query geospatial data, such as maps and location-based information.
   - **Support for Spatial Operations:** They offer specialized spatial operations and indexing for geospatial data analysis.
10. **NewSQL Database:**
    - **Scalability and ACID Compliance:** NewSQL databases aim to combine the scalability of NoSQL databases with ACID compliance, making them suitable for high-transaction-rate applications.
