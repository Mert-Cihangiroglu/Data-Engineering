# Data-Engineering
Possible  questions that can be asked in Big Data Engineering courses and interviews.

### What is Data Engineering?
- Data engineering is a term used in big data. It focuses on the application of data collection and research. The data generated from various sources are just raw data. Data engineering helps to convert this raw data into useful information.

### What is Data Modeling?
- Data modeling is the method of documenting complex software design as a diagram so that anyone can easily understand. It is a conceptual representation of data objects that are associated between various data objects and the rules.

### Can you list some types of design schemas in Data Modelling ?
- There are mainly two types of schemas in data modeling: 1) Star schema and 2) Snowflake schema.

### What is Hadoop, and why it's used?
- Apache Hadoop is an open source software framework used to develop data processing applications which are executed in a distributed computing environment.
- Applications built using HADOOP are run on large data sets distributed across clusters of commodity computers. Commodity computers are cheap and widely available. These are mainly useful for achieving greater computational power at low cost.

### What is NameNode?
 - It is the centerpiece of HDFS(Hadoop Distributed File System). It stores data of HDFS and track various files accross the clusters. The actual data isn't stored. The data is stored in DataNodes.
 
 ### Define Hadoop streaming.
 - It is a utility which allows for creation of the map and Reduces jobs and submits them to a specific cluster.
 
 ### Define Block and Block Scanner in HDFS.
 - Blocks are the smallest unit of a data file. Hadoop automatically splits huge files into small pieces. Block Scanner verifies the list of blocks that are presented on a DataNode.
 
 ### What are the steps that occur when Block Scanner detects a corrupted data block?
 - Following are the steps that occur when Block Scanner find a corrupted data block:
 1- When block scanner find a corrupted data block, DataNode report to NameNode.
 2- NameNode start the process of creating a new replica using a replica of the corrupted block.
 3- Replication count of the correct replicas tries to match with the replication factor. If the match found corrupted data block will not be deleted.
 
 
 ### Sources

-  Good source for Hadoop: https://www.guru99.com/learn-hadoop-in-10-minutes.html
