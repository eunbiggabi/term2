### R7. Identification of the problem you are trying to solve by building this particular marketplace app.

People think they take painkillers, see a doctor for treatment, or operate when they feel pain in their knees, back, wrists, etc. in their daily lives, but they do not know that a 20-dollar protector can reduce minor pain or inflammation. Furthermore, we want to be an app site that can relieve fatigue in a day by adding massage machines.

### R8. Why is it a problem that needs solving?

Body helper was created to help people suffer from minor pain. We want to help over 10,000 people **back to healthy life** and future through providing our effective and functional products. 

### R9. A link (URL) to your deployed app (i.e. website)

[Heroku Link](https://young-taiga-87851.herokuapp.com/) (Issue with database, only desplay is working)

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

- SCSS, Bootstrap & FontAwesome - Bootstrap, the world’s most popular framework for building responsive, mobile-first sites. Bootstrap was used for all styling and interactive components on the site. Bootstrap was used for its ease of use, aesthetic appeal, numerous components, JS integrations and responsive first properties. Bootstrap speeds up front end development immensely. Font Awesome is a web font containing all the icons from the Twitter Bootstrap framework, and now many more. It allows you to easily use many icons across your site that are stored remotely.



### R12. User stories for your app

![Trello](https://i.imgur.com/2lKvSbD.png)

[Trello Link](https://trello.com/b/Gm2ykgRf/eunjeont2a2-marketplace)

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


1. Model

 - User
 - User_address(Profile)
 - Product
 - Order

 These 4 model represents my marketplace app. It is a component that processes and is responsible for such data information, such as a database, initialization value, variable, etc. So these 4 model must not know any information about the view or controller. This means that when a data change occurs, the model should not have an internal property value that references the view so that the screen UI can be adjusted directly. In addition, when a change occurs, the treatment of the change notice must be implemented and reused.

2. View 

- Home / Index (Main page)
- User / Index (LogIn & SignUp page)
- Product / Index (View All Collection page)

These 3 views are that indicates user interface elements, such as input text, checkbox entries, etc. In other words, it is responsible for inputting data, objects, and displaying output, and usually consists of a front end that is viewed by users such as HTML, SCSS, and JS. This refers to a screen that users can view based on data. Views should not store the information the model has separately. It can just say that the view has the role of displaying the data on the screen when data receive it.

3. Controller 

- Home 
- Product
- User

interact with models and views. The presence of a controller prevents models and views from being directly connected to each other. In other words, it acts as a bridge between data and user interface elements. The simple rules of the controller must be known about the model or view, the model or view does not exist, and the controller is responsible for the main logic to interpret and send to each department when notified of the change

### R16. Detail any third party services that your app will use  

- Heroku - Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps. This Appliction makes use of Heroku's free service model for small projects. Heorku also streamlines deployment through its Git integration allowing updates to easily be pushed to Heroku as you would any other remote git repository.

- AWS S3 - offering over 200 fully featured services from data centers globally. Millions of customers—including the fastest-growing startups, largest enterprises, and leading government agencies—are using AWS to lower costs, become more agile, and innovate faster.
R17	Describe your projects models in terms of the relationships (active record associations) they have with each other
R18	Discuss the database relations to be implemented in your application

- Github - Last but not least it Github, a developers best friend. GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.

### R17. Describe your projects models in terms of the relationships (active record associations) they have with each other

I currently am using 4 models: Application_record, Order, Product, and User. The User model has the highest functionality through the Devise where-by Users can have multiple roles & have a standard role given once created. The Order model finds itself operating almost like a join table as it sits between Product and User. Product model I  created validation. Also, The User model divied by admin and normal user so that normal user can not create a new product. The Application Record model is used for the rails active record. Active Record automatically creates methods to allow an application to read and manipulate data stored within its tables.

### R18. Discuss the database relations to be implemented in your application

The structure of the database is very basic based on the automatic migrations through Devise, Active Storage, and My Products Migration which allows name, description, price, and references the Users tying them all in together.


### R19. Provide your database schema design

```
ActiveRecord::Schema.define(version: 2021_08_06_074705) do

  # These are extensions that must be enabled in order to support this database
  enable_extension "plpgsql"

  create_table "active_storage_attachments", force: :cascade do |t|
    t.string "name", null: false
    t.string "record_type", null: false
    t.bigint "record_id", null: false
    t.bigint "blob_id", null: false
    t.datetime "created_at", null: false
    t.index ["blob_id"], name: "index_active_storage_attachments_on_blob_id"
    t.index ["record_type", "record_id", "name", "blob_id"], name: "index_active_storage_attachments_uniqueness", unique: true
  end

  create_table "active_storage_blobs", force: :cascade do |t|
    t.string "key", null: false
    t.string "filename", null: false
    t.string "content_type"
    t.text "metadata"
    t.string "service_name", null: false
    t.bigint "byte_size", null: false
    t.string "checksum", null: false
    t.datetime "created_at", null: false
    t.index ["key"], name: "index_active_storage_blobs_on_key", unique: true
  end

  create_table "active_storage_variant_records", force: :cascade do |t|
    t.bigint "blob_id", null: false
    t.string "variation_digest", null: false
    t.index ["blob_id", "variation_digest"], name: "index_active_storage_variant_records_uniqueness", unique: true
  end

  create_table "categories", force: :cascade do |t|
    t.string "name"
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
  end

  create_table "inventories", force: :cascade do |t|
    t.integer "quantity"
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
  end

  create_table "orders", force: :cascade do |t|
    t.float "total_price"
    t.bigint "user_id", null: false
    t.bigint "product_id", null: false
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
    t.index ["product_id"], name: "index_orders_on_product_id"
    t.index ["user_id"], name: "index_orders_on_user_id"
  end

  create_table "products", force: :cascade do |t|
    t.string "name"
    t.text "description"
    t.float "discount_price"
    t.float "original_price"
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
    t.bigint "inventory_id", null: false
    t.bigint "category_id", null: false
    t.bigint "user_id", null: false
    t.index ["category_id"], name: "index_products_on_category_id"
    t.index ["inventory_id"], name: "index_products_on_inventory_id"
    t.index ["user_id"], name: "index_products_on_user_id"
  end

  create_table "user_addresses", force: :cascade do |t|
    t.string "firstname"
    t.string "lastname"
    t.string "address_line"
    t.string "city"
    t.string "postcode"
    t.bigint "user_id", null: false
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
    t.index ["user_id"], name: "index_user_addresses_on_user_id"
  end

  create_table "users", force: :cascade do |t|
    t.string "email", default: "", null: false
    t.string "encrypted_password", default: "", null: false
    t.string "reset_password_token"
    t.datetime "reset_password_sent_at"
    t.datetime "remember_created_at"
    t.datetime "created_at", precision: 6, null: false
    t.datetime "updated_at", precision: 6, null: false
    t.boolean "admin", default: false
    t.index ["email"], name: "index_users_on_email", unique: true
    t.index ["reset_password_token"], name: "index_users_on_reset_password_token", unique: true
  end

  add_foreign_key "active_storage_attachments", "active_storage_blobs", column: "blob_id"
  add_foreign_key "active_storage_variant_records", "active_storage_blobs", column: "blob_id"
  add_foreign_key "orders", "products"
  add_foreign_key "orders", "users"
  add_foreign_key "products", "categories"
  add_foreign_key "products", "inventories"
  add_foreign_key "products", "users"
  add_foreign_key "user_addresses", "users"
end

```

This is history how I add and remove migrations

![Migration](https://i.imgur.com/9NSqi6v.png)

### R20. Describe the way tasks are allocated and tracked in your project




