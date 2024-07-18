# IBM Cloud Database Services
IBM Cloud offers a range of database services to help you build, deploy, and manage your applications. 
Here are some of the key features and options:

## Relational databases
### IBM DB2
#### General Information
IBM® Db2® is the cloud-native database built to power low-latency transactions, real-time analytics and AI applications 
at scale. Built on decades of innovation in data security, governance, scalability and availability, it provides a 
single engine for database administrators, enterprise architects and developers to:
Build the next generation of mission-critical applications across any cloud, with continuous availability and zero 
downtime when migrating to hybrid deployments. Simplify development with support for all modern data types, workloads 
and programming languages. Enable faster decisions with support for open formats such as Apache Iceberg to securely 
share data and metadata across teams. Deploy AI at scale with built-in machine learning (ML) capabilities and
IBM watsonx™ integration for generative artificial intelligence (AI).

Db2® is optimized to deliver industry-leading performance across multiple workloads, while lowering administration, 
storage, development, and server costs. Db2 offers numerous features that help lower the cost of managing data by 
automating administration, reduce the cost of storage with industry leading data compression technologies, optimize 
workload execution, deliver scalability and high availability, secure data access, reduce the cost of developing and 
maintaining applications, and licensing terms for virtualized environments. Db2 offers multiple editions designed to 
meet the needs of different business environments. There are multiple Db2 database product editions – each with a 
unique combination of functionality and add-on offerings. For details of entitlement, rights, and obligations, refer to 
the license agreement for your product or offering. For details of the functionality that are included in each Db2 
database product edition, see Functionality in Db2 product editions and Db2 offerings. In Db2, all editions share the 
same code base. The only technical differences among editions are resource limitations and advanced features or tool 
sets. This common core design is intentional. In this way, applications that are written for any Db2 edition can easily 
be moved to any other Db2 edition on any operating system platform that is supported by Db2. This flexibility also 
applies to the database administrator (DBA). A DBA with skills on one edition will immediately be productive on any 
other Db2 edition.

Db2 Workgroup Server Edition is ideal for departmental, workgroup, or medium-sized business environments. It includes 
all of the functionality that is needed to efficiently process transactional workloads. This edition places limits on 
processor and memory that makes it ideal for medium sized workloads such as would be found in a department. This edition 
includes Data Server Manager Base, which requires a separate installation. It is available on either a Processor Value 
Unit, per Authorized User Single Install or per Virtual Server pricing model. You must acquire a separate user license 
for each Authorized User of this product with a minimum purchase of 5 users per server in which a copy of it is 
installed. If the Processor Value Unit pricing model is used, you must purchase the total number of Processor Value 
Units that are associated with the server or virtualization session where the it is installed.
It can be deployed in Linux®, UNIX, and Windows server environments and uses up to 16 cores and 128 GB of memory. Db2 
Workgroup Server Edition is restricted to a stand-alone physical server with a specified maximum number of Processor 
Value Units that are based on the total number and type of processor cores, as determined in accordance with the 
IBM® Express® Middleware™ Licensing Guide available at ftp://ftp.software.ibm.com/software/smb/pdfs/LicensingGuide.pdf.
The IBM Db2 Performance Management Offering can be added to the Db2 Workgroup Server Edition. It can be activated by 
registering the associated license certificate file (in addition to registering the license certificate file). For more 
information about add-on offerings, see Performance Management Offering.

Db2 Enterprise Server Edition is suitable for transactional and mixed workloads. This edition has no processor, memory, 
or database size limits, which makes it ideal for any size of workload. This edition includes all functions that are 
found in Db2 Workgroup Server Edition plus materialized query tables. This edition includes Data Server Manager Base 
which requires a separate installation. Db2 Enterprise Server Edition is available on either a Processor Value Unit or 
per Authorized User Single Install pricing model. You must acquire a separate user license for each Authorized User of 
this product with a minimum purchase of 25 users per 100 Processor Value Units. If the Processor Value Unit pricing 
model is used, you must purchase the total number of Processor Value Units that are associated with the server or 
virtualization session where the Db2 Enterprise Server Edition is installed. The IBM Db2 Performance Management Offering 
can be added to the Db2 Enterprise Server Edition. It can be activated by registering the associated license certificate 
file (in addition to registering the Db2 Enterprise Server Edition license certificate file). For more information about 
add-on offerings, see Performance management offering.

Db2 Advanced Workgroup Server Edition is similar to the Db2 Advanced Enterprise Server Edition, except that it places 
limits on processor and memory. This edition is the data server of choice for deployment in a departmental, workgroup, 
or medium-sized business environment. Db2 Advanced Workgroup Server Edition is available on either a 
Processor Value Unit, a per Authorized User Single Install or a Terabyte pricing model. You must acquire a separate user 
license for each Authorized User of this product with a minimum purchase of 20 users per socket available to the server. 
If the Processor Value Unit pricing model is used, you must purchase the total number of Processor Value Units that are 
associated with the server or virtualization session where the Db2 Advanced Workgroup Server Edition is installed. 
Db2 Advanced Workgroup Server Edition can be deployed in Linux, UNIX, and Windows server environments and uses up to 16 
cores and 128 GB of memory. Under the Terabyte pricing model, you must acquire sufficient Terabyte entitlements to cover 
the Terabytes of user data used (rounded up to the nearest terabyte). In addition, the number of required entitlements 
must be calculated separately for each database. This pricing model is intended for use with predominantly warehouse 
workloads. For that reason, you are required to use either database partitioning with a minimum of two active database 
partitions, or maintain at least 75 percent of your user data in column-organized tables. In the latter case, the 
pricing model expects that the majority of your workloads access those tables. Db2 pureScale® is not available with the 
Terabyte pricing model, but HADR capabilities are available. Server environments under this pricing model are bound to 
a 4 socket limit. The functionality that is provided by the IBM Db2 Performance Management Offering is included by 
default with the Db2 Advanced Enterprise Server Edition. The output for db2licm -l command will still show the 
“IBM Db2 Performance Management Offering” as “Not licensed”. This output is for DSMs use, in order to allow certain 
features on their end. The embedded features for IBM Db2 Performance Management Offering in Advanced Workgroup Server 
Edition are available to you.

Db2 Advanced Enterprise Server Edition is suitable for transactional, warehouse, and mixed workloads. This edition has 
no processor, memory, or database size limits, which makes it ideal for any size of workload. This edition includes all 
functions that are found in the Db2 Enterprise Server Edition plus column organized tables, in-memory database, data 
compression, workload management, replication, and distributed partitioning capability. This edition also comes with a 
full complement of warehouse tools, and Data Server Manager Enterprise. This option installs only the Db2 server. The 
included tools must be installed separately. Db2 Advanced Enterprise Server Edition is available on either a Processor 
Value Unit, a per Authorized User Single Install or a Terabyte pricing model. You must acquire a separate user license 
for each Authorized User of this product with a minimum purchase of 25 users per 100 Processor Value Units. If the 
Processor Value Unit pricing model is used, you must purchase the total number of Processor Value Units that are 
associated with the server or virtualization session where the Db2 Advanced Enterprise Server Edition is installed.
Under the Terabyte pricing model, you must acquire sufficient Terabyte entitlements to cover the Terabytes of user data 
used (rounded up to the nearest terabyte). In addition, the number of required entitlements must be calculated 
separately for each database. This pricing model is intended for use with predominantly warehouse workloads. For that 
reason, you are required to use either database partitioning with a minimum of two active database partitions, or 
maintain at least 75 percent of your user data in column-organized tables. In the latter case, the pricing model expects 
that the majority of your workloads access those tables. Db2 pureScale is not available with the Terabyte pricing model, 
but HADR capabilities are available. The functionality that is provided by the IBM Db2 Performance Management Offering 
is included by default with the Db2 Advanced Enterprise Server Edition. The output for db2licm -l command will still 
show the “IBM Db2 Performance Management Offering” as “Not licensed”. This output is for DSMs use, in order to allow 
certain features on their end. The embedded features for IBM Db2 Performance Management Offering in Advanced Enterprise 
Server Edition are available to you.

Db2 Direct Advanced Edition provides a comprehensive database solution for the enterprise with a licensing metric to 
facilitate hybrid cloud deployment. Similar to Db2 Advanced Enterprise Server Edition, this solution offers data 
warehousing, transactional and analytics capabilities in one package. It provides advanced features for storage 
optimization, in-memory computing, reliable system availability, and workload management tools. The solution also helps 
ensure high performance, actionable insight, continuous availability and reliability, at lower cost. This version 
introduces a simplified license metric, the Virtual Processor Core (VPC), which is sold as a monthly licensing charge. 
It provides flexible deployment options for either on-premises or on cloud. Db2 Direct Advanced Edition offers these 
    - features and benefits:
    - Improves application performance and analytics for faster decisions.
    - Delivers high availability and disaster recovery capabilities.
    - Provides a secure, flexible environment.
    - Interfaces with a variety of data more efficiently.
    - Improves productivity and reduces administration efforts.
Db2 Direct Advanced Edition can be deployed on Linux, UNIX, or Windows servers of any size, from one processor to 
hundreds of processors, and on both physical and virtual servers. Program charges: Db2 Direct Advanced Edition is 
available on per Virtual Processor Core (VPC) charge metric as a monthly license charge.

IBM Db2 Direct Standard Edition is a high-performance database for small or mid-size businesses, with licensing options 
for hybrid cloud deployments. It includes all Db2 Workgroup Server Edition features to provide robust data management, 
high availability, autonomic functions and security features. The solution helps ensure greater runtime performance, 
reliability and lower total cost of ownership. This version introduces a simplified license metric, the Virtual 
Processor Core (VPC), which is sold as a monthly licensing charge. It provides flexible deployment options for either 
on-premises or on cloud. Db2 Direct Standard Edition offers these features and benefits:
    - Improves application performance and analytics for faster decisions.
    - Delivers high availability and disaster recovery capabilities.
    - Provides a secure, flexible environment.
    - Interfaces with a variety of data more efficiently.
    - Improves productivity and reduces administration efforts.
Program charges: Db2 Direct Standard Edition is available on a Virtual CPU charge metric. You are restricted to 16 
virtual processor cores and 128 GB of instance memory. These restrictions are per physical or virtual server except in a 
pureScale or DPF cluster where the restrictions apply to the entire cluster.

Db2 Developer Edition
This edition offers a package for a single application developer to design, build, and prototype applications for 
deployment on any of the IBM Information Management client or server platforms. This comprehensive developer offering 
includes all the Db2 server editions, Db2 Connect Enterprise Edition, allowing you to build solutions that use the 
latest data server technologies. Program charges: The software in this package cannot be used for production systems. 
You must acquire a separate user license for each Authorized User of this product. The functionality provided by the IBM 
Db2 Performance Management Offering is included by default with the Db2 Developer Edition.

Db2 Workgroup Server Edition each require a minimum of five authorized users for each server.
Db2 Enterprise Server Edition requires a minimum of 25 authorized users per 100 PVUs 
(rounded up to the nearest 100 PVUs) that apply to the processors on which the Db2 database product is installed.
Db2 Connect has an effective minimum of 25 authorized users or concurrent users because Db2 Connect users are sold only 
in blocks of 25. You cannot purchase individual Db2 Connect user license entitlements.

#### Creating an instance on IBM Cloud
To create an instance of IBM Db2 on IBM cloud you must first log in to your IBM Cloud account. If you do not have one, 
take a moment to sign up before proceeding. Find the IBM DB2 service in the services catalogue and click on the button 
that says "Create" in order to create your instance. Choose the instance type that best suits your needs.
Your choices are: Development, Standard, or Enterprise. You also have the option of a High Availability instance which 
provides automatic failover and load balancing. Next, you must configure the instance. You can do so by choosing the 
database engine (either DB2 LUW for Linux, Unix, and Windows) or DB2 z/OS for z/OS mainframes. Then you will choose the 
storage (local storage or object storage). Local storage is on the instance's local storage, object storage is on IBM 
Cloud's object storage. Choose the Backup and Restore (automatic or manual). Finally, give the instance a name and 
description befitting the usage of the database. Choose the VPC, subnet, and availability zone for the instance
and click "Create". You might need to wait for a few minutes as the instance is being created. Once created, the 
instance can be accessed via the DB2 command line tool or a DB2 client. You can also use a DB2 GUI tool like IBM Data 
Studio.

## NoSQL databases
### IBM Cloudant
#### General Information
IBM Cloudant is a fully managed, cloud-based NoSQL database service that provides a flexible and scalable way to store 
and manage large amounts of data. It is built on Apache CouchDB and is designed to handle high traffic and large 
datasets, making it an ideal choice for applications that require real-time data processing and analytics.
It stores data as documents in JSON format. It is built with scalability, high availability, and durability in mind. It 
comes with a wide variety of indexing options that include MapReduce, IBM Cloudant Query, and full-text indexing. The 
replication capabilities make it easy to keep data in sync between database clusters, desktop PCs, and mobile devices.
Cloudant is suitable for a wide range of use cases, including:
    - Real-time analytics: Cloudant's ability to handle high traffic and large datasets makes it an ideal choice for 
                           real-time analytics and data processing.
    - IoT data storage: Cloudant's scalability and flexibility make it a great choice for storing and processing large 
                        amounts of IoT data.
    - Mobile and web applications: Cloudant's ability to handle large amounts of data and provide real-time updates 
                                   makes it a great choice for mobile and web applications that require fast data 
                                   retrieval and updates.
    - Big Data analytics: Cloudant's ability to handle large datasets and provide real-time analytics makes it a great 
                          choice for big data analytics and data science applications.
#### Creating an instance on IBM Cloud
Once you have created your IBM Cloud account, navigate to the Cloudant dashboard by clicking on the "Catalog" tab and 
selecting "Cloudant" from the list of services. Click on the "Create" button to create a new Cloudant instance. 
You will be prompted to enter the following information:
Instance name: Enter a name for your Cloudant instance.
Plan: Choose a plan that suits your needs. Cloudant offers several plans, including a free plan and paid plans with 
varying levels of storage and throughput. Region: Choose a region for your Cloudant instance. Cloudant is available 
in several regions around the world. Database name: Enter a name for your database. Once you have created your Cloudant 
instance, you will need to configure it. You can do this by clicking on the "Configure" button and entering the 
following information: Username: Enter a username for your Cloudant instance. Password: Enter a password for your 
Cloudant instance. Database settings: Configure your database settings, including the database name, storage size, and 
replication settings. Once you have configured your Cloudant instance, you can connect to it using the Cloudant 
dashboard or using a programming language such as Python or JavaScript. You can use the Cloudant API to interact with 
your database and perform CRUD (Create, Read, Update, Delete) operations.

## Graph databases
### IBM Graph
#### General Information
IBM Graph is a graph database service that provides a scalable and flexible way to store, manage, and query complex 
relationships between data entities. Graph databases are particularly well-suited for applications that require complex 
querying and analysis of relationships between data entities, such as social networks, recommendation systems, and 
fraud detection. IBM Graph is suitable for a wide range of use cases, including:
Social network analysis: IBM Graph can be used to analyze complex relationships between users in a social network, 
such as friendships, followers, and likes.
Recommendation systems: IBM Graph can be used to build recommendation systems that take into account complex 
relationships between users and items, such as movies, music, and products.
Fraud detection: IBM Graph can be used to detect complex patterns of fraudulent activity by analyzing relationships 
between transactions, users, and other entities.
Supply chain management: IBM Graph can be used to analyze complex relationships between suppliers, manufacturers, and 
customers in a supply chain.
#### Creating an instance on IBM Cloud
Once you have created your IBM Cloud account, navigate to the IBM Graph dashboard by clicking on the "Catalog" tab and 
selecting "IBM Graph" from the list of services. Click on the "Create" button to create a new IBM Graph instance. You 
will be prompted to enter the following information:
Instance name: Enter a name for your IBM Graph instance.
Plan: Choose a plan that suits your needs. IBM Graph offers several plans, including a free plan and paid plans with varying levels of storage and throughput.
Region: Choose a region for your IBM Graph instance. IBM Graph is available in several regions around the world.
Database name: Enter a name for your database.
Once you have created your IBM Graph instance, you will need to configure it. You can do this by clicking on the 
"Configure" button and entering the following information:
Username: Enter a username for your IBM Graph instance.
Password: Enter a password for your IBM Graph instance.
Database settings: Configure your database settings, including the database name, storage size, and replication 
settings.
Once you have configured your IBM Graph instance, you can connect to it using the IBM Graph API or a programming 
language such as Python or JavaScript. You can use the IBM Graph API to perform CRUD (Create, Read, Update, Delete) 
operations on your graph data.
