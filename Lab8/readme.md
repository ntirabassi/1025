## Natalie Tirabassi / December 9, 2021

## Executive Summary 
During the course of this lab I was able to explore various database models and practice requesting information from a database using SQL. I had never used this type of language before, so I was excited to be able to learn something new and apply it firsthand. I also learned about tables, columns, primary keys, and foreign keys are all ways that data can be organized and sorted so that users can access the information easily through SQL. I also learned about threats to SQL and how to combat them.

## Data, Information and Knowledge
### Compare and contrast data, information and knowledge
Data refers to the raw facts, devoid of context. It can be quantitative or qualitative, in other words, numeric or descriptive. Information is processed data that possess context, relevance, and purpose. It involves the manipulation of raw data to obtain an indication of magnitude, trends, and patterns in the data. Knowledge is human beliefs or perceptions about relationships between relevant facts or concepts. Once the data is put into context and analyzed, the consumption of information produces knowledge.
### Relational Data
#### Primary Key:
A primary key is special field or combination of fields that determines the unique record in a database. For a small company that uses two tables called customers and orders, the primary keys would be “CustomerName” and “CustomerOrder.” 
#### Relationship between customers and orders:
The customers and orders table can be related by using a foreign key. A foreign key is a field in one table that connects to the primary key data in the original table. For example, the foreign key “CustomerName” in the order table connects to the primary key “CustomerName” in the customers tables.
#### Foreign key of orders table:
The foreign key of the orders table is “CustomerName” so that it can connect to the customers table. This way, the data is successfully organized and related.
### Field Data Types
A data types tells the database what functions can be performed with the data. For example, for mathematical functions, we must tell the database that the field is a number data type. It is also important to define data type so that the proper amount of storage space is allocated for our data. For example, for a Text(50) data type, this means that 50 characters are allocated for each name we want to store.
### Big Data
#### Four "V"s of Big Data
Big Data is a collection of data that is huge in volume, yet growing exponentially with time. It can characterized by Volume, Variety, Velocity, and Variability. Volume refers to its enormous size, and plays a crucial role in determining value of data. Variety refers to heterogeneous sources and the nature of data, structured and unstructured. Velocity refers to the speed of generation of data, such as how fast the data is generated and processed to the demands, determines real potential in data. Finally, variability refers to the inconsistent which can be shown by the data at times, thus hampering the process of being able to handle and manage the data effectively.
#### Technology Driving the need for Big Data
Social media, customer services systems, storage, data preprocessing, data virtualization, stream analytics, and NoSQL databases are all some example of technologies that have driven the increased need for big data. 
## Structured Query Language (SQL) 
### RDBMS and SQL
SQL is a standard language for accessing and manipulating databases. It do tasks such as, execute queries, retrieve data, and update and delete records from a database, among many others. RDBMS stands for Regional Database Management System, and it is the basis for SQL. Its data is stored in database objects called tables, and is a collection of related data entries consisting of columns and rows. SQL allows to a user to access RDBMS.
## SQL Injections
SQL injection is a code interjection technique that could destroy a database and is one of the most common web hacking techniques. It usually occurs when you ask a user for input, such as a username or id, and instead of a name/id, the user gives you an SQL statement that you will unknowingly run on your database. For example, a hacker could get access to all the usernames and passwords on a database, by simply inserting 1=1, which is always true. SQL parameters can be used for protection against this. SQL parameters are values that the SQL engine checks to ensure that it is correct for its column and are treated literally, and not as part of the SQL to be executed. 

## Ethical and Legal Implications
### Code of Ethics
A code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group, and it is generally agreed to by all members of the group. Explicitly stating standards communicates the common guidelines to everyone in a clear manner. ACM created a code for the computing discipline because the organizations wanted to uphold its notability as an organization of honest, trustworthy and professional individuals focusing on computing. For example, one of the instructions is that “no one should enter or use another’s computer system, software, or data files without permission.” This ensures the credibility and honesty of everyone involved with the organization.
### Intellectual Property
A trademark is a word, logo, shape, or sounds that identifies a source of goods or services. A registered trademark is one that has been examined, approved, and registered with the trademark office. It allows for protection of intellectual property, which is important because it gives people an incentive to be creative and also so that no one else can steal their ideas or designs. Under copyright, the author of a work controls what can be done with the work, such as who make copies of it or display it. Copyrighting my logo is smart because then I can be the owner of my own creation, and no one else can use it or copy it without my permission. 
### Information Collection
COPPA, FERPA, and HIPAA are all acts that restrict the collection different types of information on the Internet. Websites that are collecting information from children under the age of 13 are required to comply with the Children’s Online Privacy Act (COPPA). The Family Educational Rights and Privacy Act (FERPA) is a law that protects the privacy of student education records, specifying that parents have a right to their child’s educational information until the child reaches the age of 18. Finally, the Health Insurance Portability and Accountability Act (HIPAA) is the law that specifically singles out records related to healthcare as a special calss of personal identifiable information.
## Conclusion
Database models and SQL are extremely useful in helping users to find a specific piece of information without having to sort through many different others. It is very straightforward and easy to use. During this lab I also learned about key ethical and legal implications of information systems, and how honesty, trust, and credibility is managed online. With these knowledge and tools, I now feel better equipped to access the internet safely and honestly.
