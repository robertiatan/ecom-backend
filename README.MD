# E-Commerce Backend
## Description
This is a backend for an e-commerce site. It uses Express.js API and Sequelize to interact with a MySQL database.
## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Demo](#demo)
## Installation
To install necessary dependencies, run the following command:
```npm i```
## Usage
This application is used to create, read, update, and delete data from a database.
You must have MySQL installed on your computer to use this application. Make sure you first create a .env file with your MySQL username and password. After that, log into MySQL using the command 
```mysql -u root -p``` and run the following commands:
```source db/schema.sql``` and ```quit``` to exit MySQL.
In order to seed the database, run the following command:
```npm run seed``` or ```node seeds/index.js```.
To use this application, run the following command:
```npm start``` or ```node server.js```.
## Demo
This is a link to a walk-through video that demonstrates the functionality of this application:
