## Question 1

Ruby on rails uses the MVC(Model-View-Controller) architectural pattern to allow easier maintainability throughout the application.

Looking at the overall flow of MVC, when a user accesses and requests a particular URL, the Controller receives this request, retrieves the data from the Model, and visualizes it to the user via View.

The **Controllers** interact with models and views. This presence of a controller provides a significant advantage in maintenance by avoiding situations where the Model and View are directly connected to each other. Query and import data from the model that meets the request and reflect it in the View. The **Model** handles everything related to the data. It's a function because it doesn't care what it looks like to the user. You can define the rules and functions associated with the database, create, find, and import data. The **Views** typically refer to elements necessary for front-end configurations such as html/css/javascript (almost identical to browsers viewed by actual users) which is the end result of showing the user. Views can server content in several formats, such as HTML, PDF, XML, RSS and more.

Supports the major databases - It supports MySQL, Oracle, MS SQL Server, PostgreSQL, IBM DB2, and more.