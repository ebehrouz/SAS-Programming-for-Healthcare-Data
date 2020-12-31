# SAS-Programming-for-Healthcare-Data
Longitudinal healthcare records update occurs electronically over time for a population. To manage such records, many healthcare organizations now store data and manage data in relational databases. A relational database is a type of database that utilizes a structure that allows you access to data in relation to another piece of data in the database. In a relational database, data sets are often stored into tables. Connections between the tables are carried out using foreign keys. A foreign key, for example a Patient_ID, is a unique reference that can connect one row in a table to another row in another table. The EHR database used for this project contains the following 12 SAS tables:
1.	Allergy (intolerance);
2.	Billing;
3.	Encounter;
4.	Encounter diagnosis;
5.	Exam;
6.	Health condition (problem list);
7.	Medication;
8.	Patient;
9.	Referral;
10.	Risk factor;
11.	Vaccine
12.	Vaers
These data sets, which have been artificially created for this book and the related data dictionary, are freely available to download from GitHub. 
To better understand the concepts discussed in each chapter, it is highly advisable that you download all these data sets, then create a SAS library and name it EHRData, and use them practically for the programs that are given during each chapter. Except for Vaers data set, none of the information including Patient_IDs presented in these tables are real and there is no connection between these artificial data sets with any actual EHR data sets. The source of information for Vaers data set is discussed in chapter 5.  
