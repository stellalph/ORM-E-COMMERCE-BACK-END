## 13 Object-Relational Mapping(ORM): E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The task of this project is to build the back end for an e-commerce website and configure a working Express.js API to Sequelize to interact with a MySQL database.  This application would use MYSQL2 and Sequelize packages to connect Express API to a MySQL Database and a dotenv package to use environment variables to store sensitive data.

This application would show the creation of database using MySQL with models and associations and also the API routes to perform RESTful CRUD Operations.  This would be demonstrated in the Walkthrough Video.

The URL of the GitHub repository is <strong>https://github.com/stellalph/ORM-E-COMMERCE-BACK-END.git</strong>.
and the repository name is ORM-E-COMMERCE-BACK-END.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

* This application will need the installation of node.js from the website, https://www.node.org.

* Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency 
  conflicts intelligently and initialized using <strong>npm init</strong>.  The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization.

* This application also need the installation of MySQL which is a developer-friendly open source relational databse system.  The application uses MySQL packjage and 
  sequelize package to connect Express.js to MySQL database and also the dotenv package to use environment variables to store sensitive data. Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.

  - npm install --save mysql2
  - npm i sequelize
  - npm install dotenv --save 

* Nodemon is installed as development dependency meaning that if our application ever goes in production, this package will not be included. The command to install 
  for in this case is npm i -D nodemon.        
  The purpose of this package is to watch for any changes in our files and restart the server instead of us having to do that manually ourselves. The screenshot show the working of the nodemon.  
 
  ![alt text](/assets/image01.png)

* The database models are set up with its requirements.   MySQL Workbench is installed to help with design, create and browse the database schemas, work with database      objects and insert data as well as design and run SQL queries to work with stored data.  Schemas and data from other database vendors can be migrated from database vendors to MySQL database.

* The database contains the following four models set up in accordance with the requirements for each model.  From MySQL Workbench:-

 ![alt text](/assets/image02.png)     
 
* Category 

 ![alt text](/assets/image03.png) 

* Product

 ![alt text](/assets/image04.png)

* ProductTag

![alt text](/assets/image05.png)

* Tag

![alt text](/assets/image06.png)

* For testing in Insomnia, the following folder and sub folders were set up as in the Mock-up.

![alt text](/assets/image07.png)


## Usage


## References


## License

This project is licensed under the terms of the MIT license.