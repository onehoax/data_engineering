# Andres Osorio

Software developer with emphasis on Back-End and Data Engineering. Currently a Full Stack developer working in the banking industry. I have a Background in Behaviour Analysis and experience in a wide variety of environments that have provided me with the right combination of professional and personal skills. The amount of data being created every year is growing at an exponential rate and will continue to do so; Data Engineering resonates with me because there is a need for qualified individuals to make sense of it all and I love both engineering and the patterns that arise from data. I am responsible, reliable, organized, disciplined, hard-working, goal-oriented, and always eager to learn.


## Skills

**Concepts:** OOP/FP, RDBMS/NoSQL, Data Access Patterns, OLAP/OLTP, Microservices, REST APIs, Agile, TDD

**Languages:** Java, SQL, Bash, Git, Go, JavaScript/HTML/CSS, Python, C, Eiffel

**Frameworks:** SpringBoot, Maven, Hadoop, Spark, NiFi, Node/Express/Vue, Docker, Kubernetes

**Other:** Oracle DB, PostgreSQL, GCP/AWS/Azure, Blockchain


## Jarvis Projects

Project source code: [https://github.com/OneHoax/data_engineering](https://github.com/OneHoax/data_engineering)

**Cluster Monitor** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/linux_sql)]: 

Developed a monitoring agent to keep track of a cluster's resources and usage across time; this provided the team invaluable information about decisions to scale the cluster (and each node in it) up or down. The project was implemented with Bash, PostgreSQL, and Docker.

**Core Java Apps** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/core_java)]:
      
  - Grep App: Searches for a text pattern recursively in a given directory and outputs matched lines to a file - implemented with Java 8 Streams.
  - JDBC App: Performs fundamental CRUD operations using the DAO pattern as an abstraction layer with DTOs as the actual objects encapsulating data to and from the data source.
  - Twitter App: Posts/shows/deletes Twitter posts via the Twitter REST API - designed with the well-known MVC (minus V) architecture.

**SpringBoot App** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/springboot)]: 

Developed a RESTful API using SpringBoot that simulates an online stock trading system; it retrieves stock market data from IEX Cloud and persists it into a PostgreSQL instance; this data can then be used to CRUD quote, trader, and order data against the database. This API can be consumed by front-end and mobile developers, as well as traders. The application is implemented as a microservice using SpringBoot (to manage dependencies and provide the web-server), PostgreSQL (to persist and CRUD data using DAO), and IEX Cloud (as the stock market data source); it also falls under the MVC and 3-tier architecture - it has a client tier (HTTP clients to consume API), an application tier (SpringBoot Java program which processes data), and a data tier (where data is persisted).

**Data Analytics** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/python_data_wrangling)]: 

Implemented a data analysis project to help a retail organization drive their revenue back up; specifically, the analysis segmented customers (using RFM Segmentation) into important categories to help the company develop targeted marketing strategies. Used a PostgreSQL instance as a data warehouse and Python Pandas/Jupyter to perform OLAP operations on the data and answer necessary business questions.

**Hadoop** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/hadoop)]: 

Evaluated Hadoop core components (HDFS, YARN, and MapReduce), deployed a 3-node Hadoop cluster using Google Cloud Platform Dataproc, and performed data processing/analytics using Hive and Zeppelin; leveraged the distributed storage and processing capabilities of the Hadoop ecosystem to examine the 2016 World Development Indicators dataset, optimize it, and ultimately do analytical operations on it.

**Spark** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/spark)]: 

Evaluated Spark's functionality and performance with Zeppelin on Hadoop and re-implemented the [Data Analytics project](https://github.com/OneHoax/data_engineering/tree/master/python_data_wrangling) using Azure Databricks and Spark Structured APIs; performed parallel data analytics on a cluster against customer transactional data to answer several business questions and identify important customer categories to help the client organization develop targeted marketing strategies.

**Cloud/DevOps** [[GitHub](https://github.com/OneHoax/data_engineering/tree/master/cloud_devops)]: 

Deployed the [SpringBoot App](https://github.com/OneHoax/data_engineering/tree/master/springboot) to the Azure Cloud; used Azure Kubernetes Service to create 2 identical Kubernetes clusters to serve as development and production environments; deployed the application, scaled it out/in as needed, and exposed it to the outside world by using the Kubernetes API; used Azure Container Registry to build/store Docker images for better integration with Azure services; ultimately, automated the integration and deployment process by developing CI/CD pipelines for each of the environments using Jenkins.


## Highlighted Projects
**Language Analyzer** [[GitHub](https://github.com/OneHoax/language_analyzer)]: 

Designed and implemented 1) a Java-like programming language and 2) its two associated functionalities: Java-like code generation and type checking. The project was developed on the Eiffel Testing Framework (ETF) - Eiffel is an object-oriented and contract-based language. Implemented the project with the Visitor Design Pattern because it involves a language structure (classes, attributes, methods, etc.) that is meant to be closed for modification and language operations (code generation and type-checking) which are open for modification - this fulfills the open-close principle which is a requirement to apply the visitor pattern.

**Gym Platform** [[GitHub](https://github.com/OneHoax/gym_platform)]: 

Developed a fully responsive Single-Page-Webapp that works as a platform to deliver instructional content on physical training and nutrition; it uses vue.js + materialize for the front end and node.js + firebase for the back end (authorization and deployment). It supports registering and logging in/out.


## Professional Experiences

**Full Stack Developer, CIBC (Jan 2021 – Present):**

Full Stack developer for a background screening application used for onboarding new employees. Part of a small scrum team applying agile best practices through daily stand-up meetings, JIRA boards/tickets, and development based on continuous requirement revision. The application is built on top of a vendor product from NICE Actimize and it involves work with HTML/CSS, XSL, JavaScript, Java (Maven, SpringBoot, Microservices), Oracle DB, NiFi, BASH, Git, Hadoop, and Linux. Lead developer on solutions to mitigate risks identified by the bank regarding retention of large amounts of sensitive data in the application’s DB; responsible for migration from batch feeds to querying from sources on a per-need basis through APIs.

**Data Engineer, Jarvis Consulting Group (Jun 2020 - Jan 2021):**

Worked in a small scrum team developing Data Engineering projects. Successfully contributed to all stages of product Software Development Life Cycle through continuous participation in Scrum events and Agile best practices. Implemented projects using Java, Maven, SpringBoot, Bash, RDBMS/SQL, Python, Hadoop, Spark, Docker, Git/GitHub, Kubernetes, Jenkins, and cloud services. Performed both integration and unit testing using JUnit and Mockito. Used a Linux environment (CentOS) for development.


## Education
**York University (2017-2019)**, Bachelor of Arts, Computer Science
- Top 15% (2017-2019): Faculty of Electrical Engineering & Computer Science, York University
- Chair's Honour Roll (2017-2018): Department of Mathematics & Statistics, York University
- GPA: 7.2/9.0

**George Brown College (2012-2015)**, Advanced Diploma, Behavioral Science Technology
- Dean's List (2012-2015): George Brown College
- GPA: 3.6/4.0


## Miscellaneous
- Soccer Player
