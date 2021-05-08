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

Information security does not just mean computer security. It also includes data, information, or telephone conversations.

- Authentication - Today's most popular and commonly known methods are user IDs and passwords. However, this method is easy to hack, and a better way is to check the verification number by email or text, and even by fingerprint or eye-scan. It can also make it safer by creating multiple authentication systems.


## Question 7

Let's look at some commonly used methods to ensure that data is safe and secure.

- Risk Management - The more dangerous the data is, the more protection it provides, and the less protection it may have. It is also important to make a good decision on which data to protect more closely because improved data security increases costs.

- Access Control - Access control allows users to access only the appropriate information resources once they are authenticated. Access control determines who have permission to read, modify, add, or delete information.

- Encryption - If information from external media, such as the Internet, CDs, or flash drives, data can be accessed by unauthorized users even with appropriate authentication and access control. To prevent this, encryption was created. Encryption is a processor that encodes data on transmission or storage so that only authorized users can access it. For proper use, an encoding method is agreed so that the sender and receiver can communicate appropriately, and both parties can share encryption keys to encode and decode each other's messages.


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