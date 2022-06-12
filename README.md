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

![alt text](/assets/image06.png)

* Tag

![alt text](/assets/image08.png)

* For testing in Insomnia, the following project folder, E-Commerce Back-End and sub folders were set up as in the Mock-up.

![alt text](/assets/image07.png)


## Usage

After the creation of the models and routes, run <strong>npm run seed</strong> to seed the data to the database so the routes can be tested using insomnia.

At command prompt, type in nodemon server.js (see the screenshot on nodemon) and when the App is listening on port 3001! then testing can begin with Products, Categories and Tags.

This would be demonstrated by the Walkthrough Video (using Screencastify).

Part 1 - Walkthrough Video demonstrates:- 

* the creation of schema from the MySQL shell
* the seeding of the database from the command line

<strong>Please click here for the walkthrough video - part 1</strong>.

* [Walkthrough Video Part 1](https://drive.google.com/file/d/1pOxKltqHeRW11KXqH_M0vnj1SKEacWPo/view)

Part 2 - Walkthrough Video demonstrates:-

* the "how-to-start" the application server
* the GET routes for all categories, all products and all tags being tested in Insomnia
* the GET routes for a singel category, a single product and a single tag being tested in Insomnia
* the POST, PUT, and DELETE routes for categories and products being tested in Insomnia

<strong>Please click here for the walkthrough video - part 2</strong>.

* [Walkthrough Video Part 2](https://drive.google.com/file/d/1dnUBkNuXS-s4AIYcCVpVYBSpeqgGaV2Z/view)

Part 3 - Walkthrough Video demonstrates:-

* the POST, PUT, and DELETE routes for tags being tested in Insomnia

<strong>Please click here for the walkthrough video - part 3</strong>.

* [Walkthrough Video Part 3](https://drive.google.com/file/d/1X9IDwcaOH-dafB32Y9dMq6Y2WXHakM-n/view)

## References

* Unit 13 : The Unit Ahead Materials 
  - Introduction to Object-Relational Mapping (LaunchCode)
  - Sequelize: An Introduction
  - Dotenv Methodology
  - An Introduction to Environment Variables and How to Use them
* Insomnia API Client Tutorial by Kishstats
* The Full Stack Blog - Video Submission Guide dated May 11, 2022
* Module 13: Mini Project - Travel Planner


## License

This project is licensed under the terms of the MIT license.