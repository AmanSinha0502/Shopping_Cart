Online Shopping Cart (E-Commerce Website)
Overview
This is a fully functional E-Commerce Website designed for selling electronic products online. The project enables users to browse, register, log in, manage their cart, and place orders securely. It also includes a dedicated Admin Panel to manage inventory, products, and order statuses.

Features
User Side Functionality
User Registration and Login: New users can register, and returning users can log in to access personalized features.

Product Browsing: Users can view all available products, filter by categories, and search for items.

Add to Cart: Products can be added to the cart, with options to increase/decrease item quantity.

Checkout Process: Users can proceed to checkout and simulate a payment using demo credit card input.

Order Management: Once the order is placed, users can track order and shipping status through their profile.

Email Notifications:

On successful registration

When an order is placed

When an out-of-stock item becomes available

Upon item shipment and delivery

Admin Panel Features
Product Management:

Add new products to the store

Edit existing product details

Remove products from the store

Inventory Tracking: Keep real-time count of stock availability.

Order Management:

View and process customer orders

Mark orders as shipped or delivered

Customer Notification System: Sends email updates to customers regarding product availability and order status.

Note: The payment section is for demonstration purposes only and does not connect to an actual payment gateway.

Technology Stack
Frontend
HTML

CSS

JavaScript

Bootstrap

Backend
Java (JDK 8+)

JSP (Java Server Pages)

Servlets

JDBC

Database
MySQL

Software Requirements
Java JDK 8+

Eclipse Enterprise Edition (EE)

Apache Maven

Apache Tomcat v8.0+

MySQL Server

MySQL Workbench

Git

Project Setup & Configuration
Clone the Project:

Import the project using Git in Eclipse.

Choose the master branch and finish the setup.

Database Initialization:

Open MySQL Workbench or Command Line.

Login using MySQL credentials.

Run the SQL script provided in databases/mysql_query.sql.

Configure Application Properties:

Update application.properties file with:

MySQL db.username and db.password

Email configuration using your Gmail app password (not regular password).

Build the Project:

Use Maven build with clean install goal.

Update project and fix any library issues if needed.

Run the Project:

Configure Tomcat Server in Eclipse.

Run on server and access via: http://localhost:8080/shopping-cart/

If port conflict arises, change HTTP port to a different number like 8083.

Default Credentials
Admin:

Email: admin@gmail.com

Password: admin

User:

Email: guest@gmail.com

Password: guest

Screenshots & Visuals
Home Page

Login Page

Register Page

Product Categories and Filters

Shopping Cart

Checkout and Payment

Order Tracking

User Profile

Admin Dashboard

Product Inventory Management

Shipment Tracking

Email Notification Samples

FAQs
Q1: Unable to connect to the database?

Make sure MySQL is installed and running.

Check if credentials in application.properties are correct.

Perform Maven clean install and force update the project, then restart.

Disclaimer
This project is developed for learning and demonstration purposes. Web security and real payment integrations are not implemented in this version.

Suggestions and improvements for the project are always welcome.
Thank you!
— Project Leader, Aman Kumar
