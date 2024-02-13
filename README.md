

# Zero2Hero with System Design 

Come join me as I explore the fundamentals of system design and DSA (Data Structures and Algorithms), searching for the best resources available on the internet. Together, we'll delve into these topics from the ground up, learning and discovering along the way.

# Table of Contents



- [Fundamentals](#Fundamentals)
  - [REST API vs. GraphQL](#rest-api-vs-graphql)

  - [CI/CD Pipeline Explained in Simple Terms](#cicd-pipeline-explained-in-simple-terms)
  - [Netflix Tech Stack (CI/CD Pipeline)](#netflix-tech-stack-cicd-pipeline)




## Fundamentals
### Introduction to System Design
- [Introduction to System Design](https://www.youtube.com/watch?v=FSR1s2b-l_I&list=PLTCrU9sGyburBw9wNOHebv9SjlE4Elv5a)
### Components of System Design
- [Components of System Design](https://www.youtube.com/watch?v=aSvOThsVe5w&list=PLTCrU9sGyburBw9wNOHebv9SjlE4Elv5a&index=2)
### Client Server Architecture
- [Client Server Architecture](https://www.youtube.com/watch?v=Dg1U-jwVUrg&list=PLTCrU9sGyburBw9wNOHebv9SjlE4Elv5a&index=3)
### Proxies
- [Forward Proxy](url)
- [Reverse Proxy](url)
- [Load Balancer](url)
- [API Gateway](url)

Here's a breakdown of the differences between proxy, reverse proxy, load balancer, and API gateway:
### 1.	Proxy:
-A proxy server acts as an intermediary between clients and backend servers.
-Proxies are often used to control and monitor outbound traffic from clients.
-	They can provide features such as caching, content filtering, and access control.
-	Examples include web proxies and SOCKS proxies.
-	Proxy protects the client. 
-**	Proxy isolates clients from internet**
-	Firewall
-	Better Management : 
-	Security
-	Caching
-	Encryption and decryption (IP Address)
	
### 2.	Reverse Proxy:
-	A reverse proxy server sits between clients and backend servers.
-	It intercepts incoming requests from clients and forwards them to the appropriate backend server.
-	Reverse proxies are commonly used for load balancing, SSL termination, and protecting backend servers from direct exposure to the internet.
-	Examples include NGINX, HAProxy, and Amazon ELB.
-	Proxy protects the server. 
-	**Reverse proxy isolates servers from internet**

	
### 3.	Load Balancer:
-	A load balancer distributes incoming traffic across multiple backend servers to improve scalability, availability, and performance.
-	Load balancers can operate at various layers of the OSI model, including network (Layer 4) and application (Layer 7) levels.
-	They can use different algorithms to determine how to distribute traffic, such as round-robin, least connections, or IP hashing.
-	Examples include hardware load balancers, software load balancers, and cloud-based load balancers like AWS Elastic Load Balancing (ELB) and Google Cloud Load Balancing.
### 4.	API Gateway:
-	An API gateway is a specialized type of reverse proxy that sits between clients and backend API services.
-	It acts as a single entry point for clients to access multiple APIs and provides features such as 
-	**routing**,
- 	**authentication, 
-	authorization, 
-	rate limiting, and 
-	request/response transformation.**
-	API gateways can abstract away the complexity of backend services, enforce security policies, and provide analytics and monitoring capabilities.
-	Examples include Amazon API Gateway, Kong, and Apigee., Azure API management

### Types of Databases

Databases can be categorized into several types based on their structure, functionality, and purpose. Here are some common types of databases:
### 1.	Relational Databases (RDBMS):
-	Relational databases organize data into tables with rows and columns.
-	They use structured query language (SQL) for querying and managing data.
-	Examples include MySQL, PostgreSQL, Oracle Database, Microsoft SQL Server, and SQLite.
### 2.	NoSQL Databases:
-	NoSQL databases are designed to handle large volumes of unstructured or semi-structured data.
-	They are often used in distributed systems and can scale horizontally.
-	Types of NoSQL databases include:
-	Document-oriented databases (e.g., MongoDB, Couchbase)
-	Key-value stores (e.g., Redis, DynamoDB)
-	Column-family stores (e.g., Cassandra, HBase)
-	Graph databases (e.g., Neo4j, Amazon Neptune)
### 3.	Graph Databases:
-	Graph databases are designed to represent and store data in terms of entities and their relationships.
-	They are well-suited for applications like social networks, recommendation systems, and network analysis.
-	Examples include Neo4j, Amazon Neptune, and TigerGraph.
### 4.	Time-Series Databases:
-	Time-series databases are optimized for handling time-stamped or sequential data.
-	They are commonly used for storing and analyzing data generated over time, such as sensor data, log data, and financial data.
-	Examples include InfluxDB, Prometheus, and TimescaleDB.
### 5.	Object-Oriented Databases:
-	Object-oriented databases store data in the form of objects, which encapsulate data and behavior.
-	They are suitable for applications with complex data models and object-oriented programming paradigms.
-	Examples include db4o and ObjectDB.
### 6.	In-Memory Databases:
-	In-memory databases store data primarily in RAM, enabling faster data access and processing.
-	They are commonly used for applications requiring high-speed data retrieval and real-time analytics.
-	Examples include Redis, Memcached, and VoltDB.
### 7.	Spatial Databases:
-	Spatial databases are designed to store and query spatial data, such as geographic information system (GIS) data.
-	They support spatial data types and spatial indexing for efficient spatial queries.
-	Examples include PostGIS and Oracle Spatial.

### When should u consider nosql database

### 1.	Scalability: If your application needs to handle large volumes of data and high traffic loads, NoSQL databases are often more scalable than traditional relational databases. They are designed to scale horizontally across multiple servers, allowing you to distribute data and workload effectively.
### 2.	Schema Flexibility: NoSQL databases offer flexible schemas, allowing you to store data without a predefined schema or with a schema that can evolve over time. This is particularly useful in scenarios where the data model is complex, dynamic, or subject to frequent changes.
### 3.	Semi-Structured or Unstructured Data: NoSQL databases are well-suited for storing semi-structured or unstructured data, such as JSON documents, XML, key-value pairs, or graphs. They can handle diverse data types and structures without requiring strict schema definitions.
### 4.	High Availability and Fault Tolerance: Many NoSQL databases are designed with built-in features for high availability and fault tolerance. They can replicate data across multiple nodes in a cluster, ensuring that the system remains available even in the event of hardware failures or network partitions.
### 5.	Performance: NoSQL databases are optimized for performance, especially for specific use cases such as real-time analytics, caching, and high-speed data ingestion. They can efficiently handle read and write operations at scale, making them suitable for applications with demanding performance requirements.
### 6.	Distributed Systems: NoSQL databases are often used in distributed systems and cloud environments, where data needs to be distributed across multiple regions or data centers. They provide features such as data replication, sharding, and automatic failover, making them well-suited for distributed architectures.
### 7.	Use Case Specific Requirements: Some applications have specific requirements that are better addressed by NoSQL databases. For example, document databases like MongoDB are well-suited for content management systems and real-time analytics, while graph databases like Neo4j are ideal for applications that need to model and query complex relationships.






