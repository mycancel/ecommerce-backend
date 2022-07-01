# E-commerce Backend Exercise

## Table of Contents

- [Description](#description)
- [Installation](#installation)

## Description

[Walkthrough video](https://drive.google.com/file/d/16axhrRU8OOLfztVDTozFq17S2J4Z5qWZ/view?usp=sharing)

This project contains the backend code for an e-commerce store. My contribution includes the schemas for each model found in the models folder, the associations in the index.js of the models folder, and each HTTP method (aside from product-routes.js's router.post) in the routes/api folder. For each model (products, categories, and tags), the data can be created, requested, updated, and deleted.

This application was created using starter code from the UNCC Web Development Bootcamp. It uses [Express.js](https://expressjs.com/), [Sequelize](https://sequelize.org/), [MySQL2](https://www.npmjs.com/package/mysql2), and [dotenv](https://www.npmjs.com/package/dotenv).

## Installation

1. In order to install dependencies, use ```npm install``` in the gitbash terminal when the path is in the root directory of the project.

2. If you do not have one already, add a .env file with the variables below:

        DB_NAME='ecommerce_db'
        DB_USER='<Your_username_here>'
        DB_PASSWORD='<Your_password_here>'


3. Use the MySQL shell to create the database by running ```source db/schema.sql```. 

4. In the git bash terminal, seed the database with information by using the script ```npm run seed```. 

5. The server can be run by typing ```npm start``` in the git bash terminal or by running the devDependency ```nodemon```.