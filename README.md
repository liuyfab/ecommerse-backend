# ecommerse-backend

# Description
This project is a backend for an ecommerce site using Node.js, MySQL, and Sequelize to perform CRUD(Create/Retrieve/Update/Delete) operations on the database using an Express server and its associated routes.There is no front-end, Insomnia is used for demonstration and testing.

# Link to Youtube Walkthrough video
https://youtu.be/mPv3n5mrfFI

# Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

# Installation
1. This project requires node.js. 
   To initialize by typing "npm init" into the terminal in the root directory, and then "npm install" the following packages: express.js/ MySQL2/ dotenv/ sequelize.
2. Create .env file and put the following variables:
   DB_NAME='ecommerce_db'
   DB_USER=
   DB_PW=
3. Execute the database by "SOURCE db/schema.sql"  after sarting "Mysql" (mysql -u root -p); then "npm run seed"
 

# Usage
1. To start the server: type "npm start" on the terminal command line.
2. To interface with the server: Start Insomnia and use the API methods it provides with localhost:3001. 
The following calls exist: GET all categories, products, and tags. GET individual categories, products, and tags according to their id, POST categories, products, and tags, PUT categories, products, and tags, and DELETE categories, products, and tags.

## License
  # MIT
  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

