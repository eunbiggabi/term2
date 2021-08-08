### R7. Identification of the problem you are trying to solve by building this particular marketplace app.

People think they take painkillers, see a doctor for treatment, or operate when they feel pain in their knees, back, wrists, etc. in their daily lives, but they do not know that a 20-dollar protector can reduce minor pain or inflammation. Furthermore, we want to be an app site that can relieve fatigue in a day by adding massage machines.

### R8. Why is it a problem that needs solving?

Body helper was created to help people suffer from minor pain. We want to help over 10,000 people **back to healthy life** and future through providing our effective and functional products. 

### R9. A link (URL) to your deployed app (i.e. website)


### R10. A link to your GitHub repository (repo).

[EunJEON_T2A2-Marketplace GitHub Link](https://github.com/eunbiggabi/EunJEON_T2A2)

### R11. Description of your marketplace app (website), including:

1. Purpose

Body Helper is inspired by Shopify, which is widely used in Marketplace recently. Marketplace offers only one product on a website, or several multi-items like Amazon eBay, and I want to focus on marketing capabilities in small groups to reduce the minor pain that comes from poor joints or repetitive work.


2. Functionality / features

 We are selling various products such as wrists, knees, waist, and shoulders at a discount. Description describes how it is used for each product, and an image is also attached.

- User Accounts - Body helpers allow users to create accounts with security passwords and edit profiles.

- Authentication - The public is able to view all products and specific item, However make, edit, and delet products allows to only admin user. 

- Image Upload - Each products has a product image that same as what you are going to delivery to your home  

3. Sitemap

![EunJEON_T2A2-Marketplace site map](https://i.imgur.com/hgqA0JD.png)

4. Screenshots
- Main

![Main](https://i.imgur.com/mIw8wBK.png)

- Collection

![Collection](https://i.imgur.com/zjTWfME.png)

- SignUp

![SignUp](https://i.imgur.com/5n4LEAJ.png)

- New Product

![Product](https://i.imgur.com/bD203iJ.png)


5. Target audience

This marketplace app mainly targets those who suffer from joint muscles when exercising, those who experience difficulties in their daily lives due to old age, those who suffer from repeated work, and those who want to correct their posture because of poor posture. Furthermore, those who want to relieve the fatigue of the day are also eligible.

- Someone who does repetitive work
- Someone who exercise hard
- Someone who have minor pain
- Someone who need support their joint and muscles
- Someone who want to relieve daily fatigue

6. Tech stack (e.g. html, css, deployment platform, etc)

- Ruby on rails - Ruby on Rails, or Rails, is a server-side web application framework written in Ruby under the MIT License. Rails is a model–view–controller framework, providing default structures for a database, a web service, and web pages

- PostgreSQL - PostgreSQL is a free and open-source relational database management system emphasizing extensibility and technical standards compliance built on the SQL language. It is designed to handle a range of workloads, from single machines to data warehouses or Web services with many concurrent users.

- HTML - HTML is a software solution stack that defines the properties and behaviors of web page content by implementing a markup based pattern to it. HTML5 is the fifth and current major version of HTML, and subsumes XHTML. HTML was used for our web front end.

- SCSS - scss are CSS frameworks that allow developers to quickly build web interfaces with ease. The bulk of the website styling was done with SCSS due to time constraints and unfamiliarity



### R12. User stories for your app

- Users can SignUp and SignIn
- Users can create Profile
- Users can view all product


### R13. Wireframes for your app

- Main & About

![Main & About](https://i.imgur.com/zAjEV8u.png)

- Sale Promotion & Collection

![Sale Promotion & Collection](https://i.imgur.com/dtFcuC6.png)

- Form of New Product

![Form of New Product](https://i.imgur.com/xsbvyAs.png)

- Form of User Sign In

![Form of User Sign In](https://i.imgur.com/AsYr0ye.png)

### R14. An ERD for your app

![EunJEON_T2A2-Marketplace ERD](https://i.imgur.com/oZkhXrZ.png)


### R15. Explain the different high-level components (abstractions) in your app


### R16. Detail any third party services that your app will use  

- Heroku - Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps. This Appliction makes use of Heroku's free service model for small projects. Heorku also streamlines deployment through its Git integration allowing updates to easily be pushed to Heroku as you would any other remote git repository.

- Github - Last but not least it Github, a developers best friend. GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.

- AWS S3 - offering over 200 fully featured services from data centers globally. Millions of customers—including the fastest-growing startups, largest enterprises, and leading government agencies—are using AWS to lower costs, become more agile, and innovate faster.
R17	Describe your projects models in terms of the relationships (active record associations) they have with each other
R18	Discuss the database relations to be implemented in your application

### R17. Describe your projects models in terms of the relationships (active record associations) they have with each other

I currently am using 4 models: Application_record, Order, Product, and User. The User model has the highest functionality through the Devise where-by Users can have multiple roles & have a standard role given once created. The Order model finds itself operating almost like a join table as it sits between Product and User. Through the Product model I have begun creating validation on the images and an auto re-size for any image created. For now, it ensures that Product belong to someone and can have images attached when create a new product. Also, The User model divied by admin and normal user so that normal user can not create a new product. The Application Record model is used for the rails active record. Active Record automatically creates methods to allow an application to read and manipulate data stored within its tables.

### R18. Discuss the database relations to be implemented in your application

The structure of the database is very basic based on the automatic migrations through Devise, Active Storage, and My Products Migration which allows name, description, price, and references the Users tying them all in together.


### R19. Provide your database schema design

This is same as my ERD what I have on **R14**

![EunJEON_T2A2-Marketplace schema design](https://i.imgur.com/oZkhXrZ.png)
R20	Describe the way tasks are allocated and tracked in your project

### R20. Describe the way tasks are allocated and tracked in your project




