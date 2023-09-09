# blog_project

# Description:
    Implement Application where User has many blog, and each use can see all blogs which saved in database.

# Project Structure
This Project create Blog application by use :
- MySQL local server, 
- Nodejs Express local server,
- Flutter application.

# Description for Each Section :
# 1. Database:
    - MySQL local server
    - Database Name will be blog_db
    - Folder Contain create table, Query file which use for Insert, update, delete, and search.
    - Tables and relation:
        User where each user will has many blogs.
# 2. Server:
    - Nodejs Express.
    - Feature:
        API: for read all blogs, Insert new blog, JWT Authorization, Update Blog, Login user and Sign up.
    - Server will contain middleware which will check if sent token is validate or not.
    Then will run code for specific API.
    - Design Pattern {MVC} without view folder:
        1. Middleware, 2. Controller, 3. Routes, 4. Models.
# 3. app:
    - Flutter application.
    - Feature:
        Application which will use api to connect to Nodejs Server,
        Upload New blog, Read all blog, Get Single blog Data, Create new user, Login by use email and password, update user data.
    - Design Pattern {MVVM} Folders:
        1. View, ViewModel, Model, Repository, Utils.

# Packages which Will use:
# 1. Server:
    - Express, - Mysql, - jsonwebtoken.
# 2. Flutter App:
