# why-dbms-Safa-isik
why-dbms-Safa-isik created by GitHub Classroom

What is a database and how is it different from a spreadsheet?

Fundamentally, a database is a computer program designed to store, manipulate, and retrieve information. 
Databases use tables as a means of storing and retrieving information. 
Tables are organized as columns (fields) and rows (records). 
This tabular structure is similar to spreadsheets, but unlike a spreadsheet, most databases are relational, meaning that data between tables can be linked and cross-referenced.

In a relational database, data in a table can be related according to common keys or concepts. 
Relationships are a logical connection between different tables and are established based on the interaction among these tables. 
Well-defined relationships (rules) between database tables can be established to enforce restrictions on the data. 
Tables communicate and share information, which facilitates data searchability, organization, and reporting.

Typically in a spreadsheet, the information is formatted. 
Therefore, adding new data can be tedious. Since database tables store the raw data without formatting, data entry is easier. Many databases have forms or user-interfaces designed to facilitate data entry and editing.
Mechanisms to easily retrieve data are also generally available to the database user. 
Data can be sorted based on any field and reports can be generated that contain only certain fields from each record without changing the source data. Data reports apply formatting after the data is extracted from the database.

Why a database rather than a spreadsheet?

#Data Purpose
What kind of data is being collected? Spreadsheets are great for numeric and text values in relatively low volume. 
Databases also expertly handle numeric and text values but can easily incorporate other types of information, such as images and documents. 
Databases can also accommodate high volume and large file size data downloads like those from data loggers, GPS devices, cameras, drones, and other collection devices.

#Data Volume
How much data is being collected? For long-term projects with numerous monitoring locations, millions of data points can be generated. 
Because databases store information more efficiently, databases can handle volumes of information that would be unmanageable in a spreadsheet. 
Spreadsheets have record limitations whereas databases do not. Compared to databases, spreadsheets can require a large amount of hard-drive space for data storage. 
When a spreadsheet has many fields or a large amount of data (1000s of rows), the spreadsheet can be hard to read. 
Finding specific data can be cumbersome. Relational databases use querying tools to overcome these issues.

#Editing
Is information subject to changes? Updates to databases are typically easier than spreadsheets, especially if the same information is maintained in multiple records or multiple spreadsheets. 
For example, if environmental monitoring data for project sites are stored in a series of spreadsheets and the regulatory standards are listed on each sheet, then a change to the regulatory standards requires that changes are made to all the spreadsheets.
Whereas, in a database, the regulatory standards would be updated in one table and would be available for any reporting queries of the associated data. 
In addition, a database can update records in bulk.

#Data Accessibility and Speed
Although data in spreadsheets can be sorted and filtered, a database has broad querying functionality that can retrieve all records matching select criteria, cross-reference records in multiple tables, and perform complex aggregate calculations across multiple tables. 
Therefore, databases provide a flexibility to sort and present data in a myriad of ways that would be nearly impossible to do with two-dimensional spreadsheets.
Many databases also provide means to automate query and report generation using stored procedures.

Data in separate spreadsheets cannot be easily compared and analyzed. Decisions based on these disparate sets of information can be flawed. 
When data are maintained in a centralized relational database, data is easily accessible for querying, analysis, and reporting. 
Since the database will enforce the same quality standards for any dataset, decisions can be made with confidence.

Databases are designed to refer to information without loading all the information into memory, unlike spreadsheets. 
Therefore, databases operate faster than spreadsheets when handling large datasets. And spreadsheets have memory limitations.

#Data Integrity
Data integrity is a key difference between databases and spreadsheets. Relational databases follow standardized integrity rules to ensure that the data they contain are accurate and accessible. 
Database fields can be restricted to specific data types, formats, and/or lengths. 
Referential integrity is the collective set of rules that ensures consistent and valid data within the database, including use of primary keys and establishing relationships between data tables. 
Use of valid values or reference values can further restrict data and prevent data entry errors.

#Redundancy
The database structure also avoids data redundancy. Since the data in different database tables are linked, there is little or no duplication of source data.
Frequently data in spreadsheets are copied multiple times and the same data are maintained in separate spreadsheet files, creating a nightmare to ensure accurate data when a change is required.
A database can also eliminate the problems of having numerous spreadsheets containing similar data and maintaining many copies of spreadsheets for version control.

#Error Proliferation
Preventing and efficiently identifying data errors in spreadsheets is challenging.
It is also much easier to accidentally overwrite or delete data in a spreadsheet than in a database. 
The larger and more complex the spreadsheet, the greater the possibility that the data can accidentally be modified and links broken.

#User Access and Security
Unlike spreadsheets, modern relational databases are designed for multiple users. 
For circumstances that require many users to share information, add new data, and/or make changes to data, a spreadsheet is a bad choice. 
Databases are ideal for sharing and collaboration of information. 
Since multiple people can access and update the database concurrently, a database is more efficient and the potential for errors is reduced.

Databases provide centralized data storage and offer better security. User permissions can be assigned to view data, edit data, and restrict access to privileged information.
