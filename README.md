# Online Book Store

# Table of Contents :

Introduction

Features

Technologies Used

Installation

Usage

Folder Structure

Contributing

# Introduction :

The Online Book Store is a web-based application that allows users to browse, search, and purchase books online. Admins can manage inventory, user accounts, and track sales. This project integrates various technologies, including HTML, JSP, Java, XML, and C libraries, to provide a robust and scalable solution.

# Features :

User Features:
Browse books by categories (e.g., Fiction, Non-Fiction, Academic).
Search for books using keywords.
Add books to a shopping cart and place orders.
View purchase history.

Admin Features:
Manage book inventory (add, update, delete books).
View and manage user accounts.
Track and analyze sales data.

Additional Features:
Secure user authentication and authorization.
Responsive design for mobile and desktop users.

# Technologies Used :

Frontend:
HTML, CSS, JavaScript: For user interface design and interactivity.

Backend:
JSP (Java Server Pages): For dynamic web content.
Java: For core backend logic and processing.
Servlets: For handling HTTP requests and responses.
C Libraries: For specific performance-critical functionalities.

Database:
MySQL: For data storage and management.

Additional Technologies:
XML: For configuration and data exchange.
Tomcat Server: For hosting the application.

# Installation :

Clone the Repository:
git clone https://github.com/DarkHacker28/Online_Book_store

Set Up the Database:
Import the provided SQL dump file (database.sql) into MySQL.
Update the database credentials in dbconfig.xml.

Deploy the Application:
Place the project folder in the Tomcat webapps directory.
Start the Tomcat server.

Configure Libraries:
Ensure the required C libraries are installed on your system.
Update the LD_LIBRARY_PATH (Linux) or system path (Windows) for library access.

# Usage :

Access the Application:
Open your web browser and navigate to http://localhost:8080/online-book-store.

Login/Register:
Create a new user account or log in using admin credentials for management features.

Explore:
Browse, search, and purchase books as a user.

Manage inventory and sales as an admin.

Folder Structure

online-book-store/
|-- src/
|   |-- main/
|       |-- java/
|           |-- com/bookstore/        # Java backend logic
|       |-- resources/
|           |-- dbconfig.xml          # Database configuration
|-- web/
|   |-- WEB-INF/
|       |-- web.xml                  # Web application descriptor
|   |-- jsp/
|       |-- user/                    # JSP files for user interface
|       |-- admin/                   # JSP files for admin interface
|-- lib/                             # External libraries (C, Java)
|-- README.md                        # Project README file
|-- database.sql                     # Database schema and initial data

# Contributing :

We welcome contributions to enhance the Online Book Store. Here’s how you can help:

Fork the repository.

Create a new branch for your feature (git checkout -b feature-name).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-name).
Open a Pull Request.


# Acknowledgments :
Special thanks to the open-source community for libraries and resources that made this project possible.
