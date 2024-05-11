# Ecommerce_Backend
  
  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
  
  ## Description

  Demo Link: https://drive.google.com/file/d/1Z0CiXePlWwogvCzNUKpEH8PhAFMzrqte/view?usp=drive_link

  This project is a robust and scalable solution for building and managing a database-driven RESTful API using Express.js, Sequelize, and PostgreSQL. It facilitates seamless communication between the client and server while ensuring efficient database operations.

  Key Features:

  Environment Variable Configuration: The project provides a convenient way to configure essential database connection details, including the database name, PostgreSQL username, and password. These sensitive credentials are stored securely in an environment variable file, ensuring the safety and integrity of the database connection.

  Database Initialization: Upon configuration, the application facilitates the creation of a development database and seeds it with test data. With simple schema and seed commands, users can swiftly set up a working environment, ready for development and testing.

  Server Invocation and Model Synchronization: Once the database is initialized, initiating the application triggers the server to start, establishing communication with the client. Additionally, Sequelize models are automatically synchronized with the PostgreSQL database, ensuring that any changes to the data model are reflected accurately in the database structure.

  RESTful API Endpoints: The API offers a variety of endpoints to interact with the database. Specifically, it supports GET routes for retrieving data related to categories, products, and tags. The data returned by these routes is formatted in JSON, ensuring compatibility with a wide range of clients.

  CRUD Operations: The API seamlessly handles CRUD (Create, Read, Update, Delete) operations through POST, PUT, and DELETE routes. Users can leverage tools like Insomnia Core to test these routes, enabling them to create, update, and delete data within the database effortlessly.

  Benefits:

  Scalability: The architecture of the project allows for easy scalability, accommodating growing data volumes and evolving business requirements.

  Flexibility: Developers have the flexibility to customize and extend the API according to specific project needs, thanks to the modular structure of Express.js and Sequelize.

  Reliability: By leveraging Sequelize's ORM capabilities and PostgreSQL's robustness, the project ensures reliable data storage and retrieval, minimizing the risk of data loss or corruption.

  In conclusion, this project provides a comprehensive solution for building and managing a high-performance Express.js API integrated with Sequelize and PostgreSQL. It streamlines the development process, empowers developers with powerful database management capabilities, and delivers a seamless experience for end-users interacting with the API.


  
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributions](#contributions)
  * [Testing](#testing)
  * [Contact Me](#contact-me)
  

  ## Installation

  npm i 

  ## Usage

  Open file, npm i dependancies, open terminal from db folder  ,   sign  into  postgres, \i schema.sql, open terminal from main server.js, seed db with npm run seed.

  
  ## License 
  This project is licensed with MIT

  ## Contributions

  branch and create pull request

  ## Testing

  NA

  ## Contact Me

  Check out my github here: https://github.com/Abbate11 Or email me at: Christian@myabbate.com

  