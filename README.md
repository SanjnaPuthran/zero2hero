

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



