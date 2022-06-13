# E-Commerce Back End

## Description 
Refactor starter-code to build the back-end for an e-commerce site, including configuring a working Express.js API using Sequelize to interact with a MySQL database. 


## Technologies Used
- JavaScript
- Node.js
- Express.js
- MySQL2
- Sequelize
- DotENV
- Router
- Nodemon

## Local Installation & Usage

To use this app, you will need a MySQL Workbench account, and to have the app installed on your machine. Documentation with installation instructions are available [here.](https://dev.mysql.com/doc/workbench/en/wb-installing.html) 

To test the API routes in this app, you may wish to have an Insomnia account and to have the app installed on your machine. Documentation and instructions are available [here.](https://support.insomnia.rest/article/156-installation1) 

STEP 1

     Clone this E-Commerce-Back-End repo to your machine.

STEP 2

From Visual Studio Code or the code editor of your choice:

     Open the repo.  
     Locate and open the .env.EXAMPLE file, located in the root directory.
     Add your own MySQL Workbench Username and Password to the env.EXAMPLE file.
     Re-name the file to .env (i.e. remove .EXAMPLE).
     Save your changes.
     Locate and open db\schema.sql.
     Copy and paste the database schema into a new MySQL Workbench query tab and run it. Refresh and view your updated schemas to ensure that ecommerce_db now appears.

STEP 3

From your terminal, run:

    npm i
    npm run watch

STEP 4: API ROUTE TESTS

From your terminal, run:

    npm run seed

## Questions
For inquiries, please contact [Khari Robertson](https://github.com/krober45).