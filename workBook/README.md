## Question 1

Ruby on rails uses the MVC(Model-View-Controller) architectural pattern to allow easier maintainability throughout the application.

Looking at the overall flow of MVC, when a user accesses and requests a particular URL, the Controller receives this request, retrieves the data from the Model, and visualizes it to the user via View.

The **Controllers** interact with models and views. This presence of a controller provides a significant advantage in maintenance by avoiding situations where the Model and View are directly connected to each other. Query and import data from the model that meets the request and reflect it in the View. The **Model** handles everything related to the data. It's a function because it doesn't care what it looks like to the user. You can define the rules and functions associated with the database, create, find, and import data. The **Views** typically refer to elements necessary for front-end configurations such as html/css/javascript (almost identical to browsers viewed by actual users) which is the end result of showing the user. Views can server content in several formats, such as HTML, PDF, XML, RSS and more.

Supports the major databases - It supports MySQL, Oracle, MS SQL Server, PostgreSQL, IBM DB2, and more(Adrian Mejia Blog. 2021).


## Question 2

The database we are going to looking for is SQlite. It is widely used and it is the default database when a Ruby on Rails application is created.

Pros

- One of the biggest advantages of SQlite is that it is practicable almost anywhere. SQLite has been ported to a variety of platforms, including Windows, MacOS, Linux, iOS, and Android.

- SQLite is the traditional table-oriented relational database role. SQLite supports transactions and atomic behavior so that any program crashes or outages do not compromise the database.

- SQLite is a single standalone binary, making it easy to deploy with apps and move with apps as needed. Each database created by SQLite also consists of a single file, which can be compressed or optimized with SQL commands.

- It has excellent portability. Unlike other common databases that store data in large batches of isolated files, SQLite stores the entire data in a single file. As a result, these files can be located anywhere in the directory hierarchy and can be shared via removable disks or file transfer protocols.

Cons

- There is a limit to concurrency. Multiple processes can access and query SQLite databases at the same time, but only one process can change the database at any given time. In other words, SQLite supports greater concurrency than most other embedded database management systems, but not as much as RDBMS with the same client-server structure as MySQL and PostgreSQL.

- User Management does not exist. The database system provides users with predefined access to databases and tables. Because SQLite reads and writes ordinary disk files directly, the only access that is applicable is the typical access rights of the underlying operating system. This makes SQLite unsuitable for applications that require special access.

- SQLite is less secure than other RDBMSs. Using servers might be safer from bugs in client applications than serverless databases such as SQLite. For example, if you are using a server, an invalid pointer on the client cannot cause server memory corruption. In addition, because servers are a single persistent process, client-server databases can control data access more precisely than serverless databases(www.javatpoint.com. 2021).

## Question 3

If you proceed without any plan when you proceed with a development project, it is easy to fail and not complete it within the deadline. This is especially true when working on a team project. It takes a lot of time to gather ideas and it is not easy to find a compromise between various opinions. Even if we gather opinions, there will be many disruptions in the process of the project. As such, the initial plan takes too much time and money, and the development process is prolonged, resulting in problems that result in no results or incorrect results. One of the methodologies used to solve these problems is Agile project(Planio. 2021).

The Agile project process is a conceptual methodology for development, characterized by repetitive development by dividing the duration of the development project into short periods. It was popular among software developers first, and now we use a lot of Agile in other fields. You can guess what purpose Agile was made for by looking at the Agile Declaration below.


- Divide the entire project development period into several short periods.

- That short development period is good for achieving only the set goals.

- During the development period, we only act to achieve our goals. I don't make anything else by falling sideways.

- Have a daily pre-work meeting. During this time, share your development situation and what to do today. You can talk about the difficulties you feel while developing. If you share the situation every day, you can easily see how far you've come to achieve your goals. Some team members finish their work early and others don't. In that case, you can adjust the workload for each person. 

If you apply Agile in this way, you can easily check the progress of the project every day and know the completion of the project, so you don't have to count the nights at the end(COSMO CONSULT. 2021).

## Question 4

Source control/version control is the activity of tracking and managing code changes. The system provides an operational record of code development and helps resolve conflicts that arise when merging contribution codes from multiple sources.

Whether you're writing your own simple applications or working as a team on a large software development project, source control is an essential component of the development process. The source code management system allows you to track code changes, check the history of modifications to code, and revert to earlier versions of your project when necessary. The source code management system can collaborate with teams to write code, isolate their work until ready, and identify who made the changes and what changes were made to resolve the problem quickly. Source code management systems simplify the development process and provide centralized sources for all code(Simpleprogrammer.com. 2021).

## Question 5

The competitive edge of software is in quality and the best way to ensure quality is to invest in testing. Generally, strict application of tests may seem to cost more to development schedules or costs, but in practice, they help identify and prevent defects that occur in advance, and contribute greatly to cost savings.

The ISO/IEC/IEEE 29119 Software Testing is an internationally recognised standard to test software which can be used within the development life cycle by any company (Eriksson, 2021).

1. Test Plan -  A detailed document summarizing test strategies, objectives, timelines, expectations, and resources required for output, serving as a blueprint for performing processors that monitor and control.

2. Test Analysis/Design - Key points are the test conditions, how to access the test, and the number of times it is tested. Also, test design as a process combines years of experience by test managers with similar projects, tester knowledge of systems/features under test, and general practice of testing at a certain point in time.

3. Test Execution - Verify that it works as expected in the order of test cases created in the implementation phase. If it's an unexpected result, you have to make evidence such as capture and manage it as an issue. It should also analyze the cause of the issue and identify other functions affected by the scope of the correction.

4. Test exit criteria/Closure - If you meet the test end criteria defined in the test plan/analysis step, share the test end with team. There will be many termination criteria, but if the progress of the set test case reaches 100%, or if it is possible to respond later after agreement with officials even if there is a specific issue, the test can usually be terminated. Afterwards, if the test is needed not only in the test environment but also in the actual environment, the test termination is shared and the test is returned to the test execution stage and checked according to the set scenario (smartbear.com, 2021).

## Question 6 

Information security does not just mean computer security. It also includes data, information, or telephone conversations. Also, all information system owners are responsible for considering security controls throughout their information systems, from initial planning to service retirement.

- Authentication - Today's most popular and commonly known methods are user IDs and passwords. However, this method is easy to hack, and a better way is to check the verification number by email or text, and even by fingerprint or eye-scan. It can also make it safer by creating multiple authentication systems.

Information systems that store or process data must leverage multi-factor authentication through managed authentication services. If this is not possible, the use of multi-factor authentication by third parties is permitted(Oneit.uncc.edu. 2021).


## Question 7

Let's look at some commonly used methods to ensure that data is safe and secure.

- Risk Management - The more dangerous the data is, the more protection it provides, and the less protection it may have. It is also important to make a good decision on which data to protect more closely because improved data security increases costs.

- Backups - It is intended to prevent possible data loss due to user or technical malfunction. It is important that backups be updated regularly. These backups must be stored in a secure location and can also be encrypted.

- Encryption - If information from external media, such as the Internet, CDs, or flash drives, data can be accessed by unauthorized users even with appropriate authentication and access control. To prevent this, encryption was created. Encryption is a processor that encodes data on transmission or storage so that only authorized users can access it. For proper use, an encoding method is agreed so that the sender and receiver can communicate appropriately, and both parties can share encryption keys to encode and decode each other's messages.

- Pseudonymisation - It is a way to secure personal data. There is still useful data, but it does not include identifiable information. Because people cannot be identified directly from aliased data, the procedure is much simpler and the risk is greatly reduced in the case of data breaches or losses.

- Access Control - Access control allows users to access only the appropriate information resources once they are authenticated. Access control determines who have permission to read, modify, add, or delete information.

- Destruction - The time may come to discard the data you have. These data are under GDPR, you have an obligation to delete data that you do not need, and sensitive data guarantees a more comprehensive method of destruction(GDPR Informer. 2021).

## Question 8

Data users have rights and responsibilities to access and use integrated data.

- Data users can consult with the data manager about any significant changes or updates to the data integration project.

- It is eligible for adequate training in dealing with legislative frameworks and security requirements. Training materials are determined by integrating institutions through possible input, advice and support provided by data managers. Data users also have access to a variety of self-help tools to enhance their understanding of Commonwealth commitments.

- Data users should know and understand the sanctions applied to attempts to distribute output or misuse data that may be distinct from attempts to identify individuals or organizations.

- Data users can receive approval or rejection notifications from the Data Manager, and data guardians have the right to approve or reject all or part of the project proposal.

- Data users are responsible for paying the data manager for recovery, if applicable, and the data user and data manager are responsible for ensuring that the data set is used for authorized purposes only(Toolkit.data.gov.au. 2021).

## Question 9

Relational databases are currently one of the most commonly used databases. It consists of a table, indicating the relationship between key and value. The table consists of rows and columns. Each column has its own name and its own type. These columns are also called field or attribute. A row means a bundle of related data. All rows in a table have the same number of columns, also called tuple or record.

Relational databases are fast in classifying, sorting, and navigating data, are as reliable as they have been used for a long time, and guarantee the integrity of the data under any circumstances. Relationships between tables can be divided by the number of tables you relate to:

- One-to-one relationships - It's easiest to visualize. In this relationship, there is only one record on each side of the relationship.

- One-to-many relationships - There is one record on one side of the relationship, and zero, one, or many on the other.

- Many-to-many relationships - This is the most flexible type of relationship. There are zero, one or many records on one side of the relationship and zero, one or many records on the other.

Schema is a blueprint for designing a table. These schemas must represent items and types for each column of the table, as well as primary and foreign keys(Smartsheet. 2021).

## Question 10

Integrity of data refers to the maintenance of accuracy, consistency, and validity of data. Maintaining the integrity of the data is an important function of the database management system and maintains the integrity of the data, primarily by limiting the operations applied to the data. There are four types of integrity that the database refers to:

- Entity integrity - Every table must have a column selected as the primary key. Fields selected as primary keys must have unique values, and do not allow empty values.

- Referential integrity - The relationship between tables must be consistent so that the foreign key of one table matches the primary key of the table referencing that key. As a result, if the primary key changes, all foreign keys referenced must be changed to match.

- Domain integrity - To ensure the integrity of the fields present in the table, defining the type of field, acceptance of NULL values, etc., and ensuring that the correct data is entered.

- Integrity rule - In a database, integrity rules refer to all the constraints to protect the integrity of data. Business rules apply differently to each user using a database, but integrity rules are common rules across databases.

A foreign key is the only key in one table that can identify records from another table. Foreign keys are used to refer to records from one table to records from another table. 

Between tables in a reference relationship, problems related to the reference integrity described above can occur. Foreign keys avoid problems related to reference integrity through these constraints(Eng. 2021).

## Question 11

- Insert - Used to add one or more rows to a database table. You must specify a table to insert rows, a column to populate, and a value to insert.

- Remove - Used to change column values for one or more database table rows. You need a table name to update, a SET clause to specify the columns to update, and a WHERE clause to specify the rows to include in the update task.

- Update - used to remove one or more rows from the database table. A WHERE clause specifying the table name to update and the rows to include in the update operation is required.

- Merge - Provides a means to perform INSERT, UPDATE, or Delete operations based on source data from another table in one statement. The advantage of using MERGE statements is that they can pass through data rather than pass for each task(Essentialsql.com. 2021).


## Reference

### Q1

Adrian Mejia Blog. 2021. Ruby on Rails Architectural Design. [online] Available at: <https://adrianmejia.com/ruby-on-rails-architectural-design/> [Accessed 30 June 2021].

### Q2

www.javatpoint.com. 2021. SQLite Advantages and Disadvantages - javatpoint. [online] Available at: <https://www.javatpoint.com/sqlite-advantages-and-disadvantages> [Accessed 29 June 2021].

### Q3

COSMO CONSULT. 2021. Agile Methodology for a successful software implementation. [online] Available at: <https://www.cosmoconsult.com/business-and-it-consulting/implementation-methodologies-and-implementation-consulting/agile-implementation-methodology/> [Accessed 8 May 2021].

Planio. 2021. The Ultimate Guide to Implementing Agile Project Management (and Scrum) | Planio. [online] Available at: <https://plan.io/blog/what-is-agile-project-management/> [Accessed 8 May 2021].

### Q4

Simpleprogrammer.com. 2021. [online] Available at: <https://simpleprogrammer.com/software-developers-know-source-control/> [Accessed 8 May 2021].

### Q5

Eriksson, U., 2021. Software Testing Process – Basics of Software Testing Life Cycle | ReQtest. [online] ReQtest. Available at: <https://reqtest.com/testing-blog/the-a-to-z-guide-to-the-software-testing-process/> [Accessed 23 June 2021].

smartbear.com. n.d., 2021 Test plan vs Test design: What's the difference?. [online] Available at: <https://smartbear.com/test-management/test-design-vs-test-plan/> [Accessed 23 June 2021].

### Q6

Oneit.uncc.edu. 2021. Standard for Security Requirements of Information Systems | Office of OneIT | UNC Charlotte. [online] Available at: <https://oneit.uncc.edu/iso/standard-security-requirements-information-systems> [Accessed 30 June 2021].

### Q7

GDPR Informer. 2021. 6 Essential Data Protection Methods - GDPR Informer. [online] Available at: <https://gdprinformer.com/gdpr-articles/6-essential-data-protection-methods> [Accessed 30 June 2021].

### Q8

Toolkit.data.gov.au. 2021. Data Integration - Roles and responsibilities of data users - Data.gov.au. [online] Available at: <https://toolkit.data.gov.au/Data_Integration_-_Roles_and_responsibilities_of_data_users.html> [Accessed 30 May 2021].

### Q9

Smartsheet. 2021. All about Relational Database Models | Smartsheet. [online] Available at: <https://www.smartsheet.com/relational-database-modeling> [Accessed 30 June 2021].

### Q10 

Eng, A., 2021. Chapter 9 Integrity Rules and Constraints. [online] Opentextbc.ca. Available at: <https://opentextbc.ca/dbdesign01/chapter/chapter-9-integrity-rules-and-constraints/> [Accessed 26 June 2021].

### Q11

Essentialsql.com. 2021. Learn how to add, remove, or modify values in SQL table. [online] Available at: <https://www.essentialsql.com/introduction-sql-server-data-modification-statements/> [Accessed 14 May 2021].