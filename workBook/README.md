## Question 1

Ruby on Rails allows easier maintenance across the entire application. Looking at the overall flow of the MVC and requesting access to a specific URL that the user wants, controller receives these request and imports data from the model to visualize it to the user via View.

**Model** represents information and data of the application. It is a component that processes and is responsible for such data information, such as a database, initialization value, variable, etc. The model must keep the all of data that the users want to edit, and must not know any information about the view or controller. This means that when a data change occurs, the model should not have an internal property value that references the view so that the screen UI can be adjusted directly. In addition, when a change occurs, the treatment of the change notice must be implemented and reused.

**View** is that indicates user interface elements, such as input text, checkbox entries, etc. In other words, it is responsible for inputting data, objects, and displaying output, and usually consists of a front end that is viewed by users such as HTML, CSS, and JS. This refers to a screen that users can view based on data. Views should not store the information the model has separately. It can just say that the view has the role of displaying the data on the screen when data receive it.

**Controller** interact with models and views. The presence of a controller prevents models and views from being directly connected to each other. In other words, it acts as a bridge between data and user interface elements. The simple rules of the controller must be known about the model or view, the model or view does not exist, and the controller is responsible for the main logic to interpret and send to each department when notified of the change(Adrian Mejia Blog. 2021).

## Question 2

SQLite is a built-in database for Ruby on Rail. So I will identify a SQLite database.


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

Agile is a software development method for developing and continuing to provide real-world operational software through rapid repetitive operations. However, Agile is not exactly a set of regulations that inform the work needed to develop software. Rather, it is a view of collaboration and workflow, and a value system that guides us through choices about what and how we make it. Specifically, the key to agile software development methodology is to quickly deliver small components of working software to improve customer satisfaction. These methods focus on continuous development utilizing adaptive approaches and teamwork. In general, agile software development consists of small teams organized by software developers and business people themselves, favoring a lightweight approach and actively embracing change at all stages of the lifecycle. You can see what Agile's purpose is in the declaration below.


- Divide the entire project development period into several short periods.

- That short development period is good for achieving only the set goals.

- During the development period, we only act to achieve our goals. I don't make anything else by falling sideways.

- Have a daily pre-work meeting. During this time, share your development situation and what to do today. You can talk about the difficulties you feel while developing. If you share the situation every day, you can easily see how far you've come to achieve your goals. Some team members finish their work early and others don't. In that case, you can adjust the workload for each person(COSMO CONSULT. 2021).

In summary, first, personal interactions should be prioritized over processes and tools. Second, work software takes precedence over comprehensive documents. Third, collaboration with customers takes precedence over contract negotiations. Finally, responding to changes takes precedence over the next plan.

## Question 4


It stores changes to the code, allowing the history of changes and the operator to track them, and making them easier to change to past codes. Source control is an essential factor, whether it is simple work or cooperation as a large project team. That way, you can isolate your work, track who made the changes and what changes were applied, and resolve problems quickly. Version control systems are on the market, but the most recommended are Git and Mercury(Simpleprogrammer.com. 2021). 

In summary, as described above, source code is easy to back up and recover to the previous source in the event of a bug. It is also convenient to merge sources when different projects are being carried out simultaneously from the same source, and it is possible to determine who changed the elements from what trial to what second.


## Question 5

ISO/IEC/IEEE 29119 software testing is an internationally recognized standard for testing software available to all companies within the development lifecycle(Eriksson, 2021).

For test processing, the following basic steps are followed.

1. Test strategy/Test planning- This involves producing a document which describes the test objectives and overall approach.

2. Test Analysis/Test Design - This involves the design of the tests by identifying the conditions that will be necessary.

3. Implementation/Execution - The execution of the test involves the running of the specified test on the computer system by using an automated test tool or manually.

4. Evaluating Exit Criteria and Reporting- This process involves evaluating the data when the test is done. This helps assess if more testing is needed or gives information so a summary report for stakeholders can be written.

5. Test Closure Activities- This happens when software is delivered. However, it can be used in other circumstances such as a project been cancelled or a maintenance release or update is done. This last step is done to check which planned deliverables were achieved to ensure all incident reports are resolved(smartbear.com, 2021).


## Question 6 

- User authentication requirements - is the verification of an active human-to-machine transfer of credentials required for confirmation of a user’s authenticity. User authentication is performed in almost all human-to-computer interactions other than guest and automatically logged in accounts. Authentication authorizes human-to-machine interactions on both wired and wireless networks to enable access to networked and Internet connected systems and resources. The reliability of authentication is affected not only by the number of factors involved but also the specific technologies and the manner in which they are implemented. Well-designed and appropriately enforced implementation rules can help ensure the security of user authentication.

- Access provisioning - involves coordinating creation of user accounts, password management, email authorizations, and other tasks. A user may be granted the ability to view, create, or modify files based on specific security and role parameters. When done correctly, provisioning encompasses the entire lifecycle, including changing roles and retiring user accounts across all systems.

- Authorization processes - is the process of establishing if the user (who is already authenticated), is permitted to have access to a resource. It determines what a user is and is not allowed to do. is a security mechanism used to determine user/client privileges or access levels related to system resources, including computer programs, files, services, data and application features. Authorization is normally preceded by authentication for user identity verification(Oneit.uncc.edu. 2021).


## Question 7

Let's look how to protect information and data in general and how to apply it to projects

- Risk Management - The more dangerous the data is, the more protection it provides, and the less protection it may have. It is also important to make a good decision on which data to protect more closely because improved data security increases costs.

- Backups - It is intended to prevent possible data loss due to user or technical malfunction. It is important that backups be updated regularly. These backups must be stored in a secure location and can also be encrypted.

- Encryption - If information from external media, such as the Internet, CDs, or flash drives, data can be accessed by unauthorized users even with appropriate authentication and access control. To prevent this, encryption was created. Encryption is a processor that encodes data on transmission or storage so that only authorized users can access it. For proper use, an encoding method is agreed so that the sender and receiver can communicate appropriately, and both parties can share encryption keys to encode and decode each other's messages.

- Pseudonymisation - It is a way to secure personal data. There is still useful data, but it does not include identifiable information. Because people cannot be identified directly from aliased data, the procedure is much simpler and the risk is greatly reduced in the case of data breaches or losses.

- Access Control - Access control allows users to access only the appropriate information resources once they are authenticated. Access control determines who have permission to read, modify, add, or delete information.

- Destruction - The time may come to discard the data you have. These data are under GDPR, you have an obligation to delete data that you do not need, and sensitive data guarantees a more comprehensive method of destruction(GDPR Informer. 2021).

## Question 8

Let us examine the legal obligations associated with user data processing and how the project is carried out.

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

## Question 12

a - Instagram

- React Native -iOS & Android apps
- Python (Django framework) & HTML5JavaScript -server-side
- Computing services -Amazon S3, Amazon, EBS, Amazon EC2
- Database -PostgreSQL (Medium. 2021).

b - Instagram was aquired by Facebook for scalability. There are many data centers built by facebook which was released to the public as part of the Open Compute Project. There are now many data centres to handle the massive amounts of the data.

c - Some examples of technoology interaction within the application include

- React/React Native- Instagram uses React to develop their front end which interacts witht their users.
- Python Django- Which is the framework it is built upon
- PostgreSQL- is the database which helps store all the data models.

d - For instagram consider a graph where the nodes are people/users and there are multiple kinds of verticies which are.

- v1: The people N followers (undirected) 
- v2: The people who's profile was visited(directed, weight by visitor number) 
- v3: The people who interact with posts by sharing 
- v4: The people who liked/commented/shared on N's activity(directed, weighted by a formula based on the number of actions of different kinds) 
- v5: The people mentioned in a post/comment of N(directed)

N is a node. Based on the attributes of this graph and the "populatrity" of the person is calculated through a formula for marketing purposes.

e - Instagram has many entites which need to be tracked such as likes, users, posts, comments, tags and followers. This is to help calculate the algorithm as said above to determine a person popularity.

f - Firstly the user can have many followers, posts, likes and comments. A posts and likes belongs to as user. A post can have many tags and tags belongs to a post as well as comments. Comments can have many tags and tags can belong to a comment. Comments also belong to posts and a post can have many comments.


## Reference

### Q1

Adrian Mejia Blog. 2021. Ruby on Rails Architectural Design. [online] Available at: <https://adrianmejia.com/ruby-on-rails-architectural-design/> [Accessed 19 June 2021].

### Q2

www.javatpoint.com. 2021. SQLite Advantages and Disadvantages - javatpoint. [online] Available at: <https://www.javatpoint.com/sqlite-advantages-and-disadvantages> [Accessed 19 June 2021].

### Q3

COSMO CONSULT. 2021. Agile Methodology for a successful software implementation. [online] Available at: <https://www.cosmoconsult.com/business-and-it-consulting/implementation-methodologies-and-implementation-consulting/agile-implementation-methodology/> [Accessed 19 June 2021].

Planio. 2021. The Ultimate Guide to Implementing Agile Project Management (and Scrum) | Planio. [online] Available at: <https://plan.io/blog/what-is-agile-project-management/> [Accessed 04 June 2021].

### Q4

Simpleprogrammer.com. 2021. [online] Available at: <https://simpleprogrammer.com/software-developers-know-source-control/> [Accessed 20 June 2021].

### Q5

Eriksson, U., 2021. Software Testing Process – Basics of Software Testing Life Cycle | ReQtest. [online] ReQtest. Available at: <https://reqtest.com/testing-blog/the-a-to-z-guide-to-the-software-testing-process/> [Accessed 23 June 2021].

smartbear.com. n.d., 2021 Test plan vs Test design: What's the difference?. [online] Available at: <https://smartbear.com/test-management/test-design-vs-test-plan/> [Accessed 23 June 2021].

### Q6

Oneit.uncc.edu. 2021. Standard for Security Requirements of Information Systems | Office of OneIT | UNC Charlotte. [online] Available at: <https://oneit.uncc.edu/iso/standard-security-requirements-information-systems> [Accessed 24 June 2021].

### Q7

GDPR Informer. 2021. 6 Essential Data Protection Methods - GDPR Informer. [online] Available at: <https://gdprinformer.com/gdpr-articles/6-essential-data-protection-methods> [Accessed 24 June 2021].

### Q8

Toolkit.data.gov.au. 2021. Data Integration - Roles and responsibilities of data users - Data.gov.au. [online] Available at: <https://toolkit.data.gov.au/Data_Integration_-_Roles_and_responsibilities_of_data_users.html> [Accessed 28 June 2021].

### Q9

Smartsheet. 2021. All about Relational Database Models | Smartsheet. [online] Available at: <https://www.smartsheet.com/relational-database-modeling> [Accessed 30 June 2021].

### Q10 

Eng, A., 2021. Chapter 9 Integrity Rules and Constraints. [online] Opentextbc.ca. Available at: <https://opentextbc.ca/dbdesign01/chapter/chapter-9-integrity-rules-and-constraints/> [Accessed 26 June 2021].

### Q11

Essentialsql.com. 2021. Learn how to add, remove, or modify values in SQL table. [online] Available at: <https://www.essentialsql.com/introduction-sql-server-data-modification-statements/> [Accessed 30 June 2021].

### Q12

Medium. 2021. Technology stack behind Instagram. [online] Available at: <https://medium.com/@selen2802/technology-stack-behind-instagram-215a8c044664>[Accessed 2 July 2021].