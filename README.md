# E-Commerce Backend

## Description

This is the back end for a e-commerce website.

The user must add the database name and their MySQL username and password to an environment variable. Then they are able to connect to that database using Sequelize.

They can enter schema and seed commands and the database will be created and seeded with test data.

They can enter the command to start the application which will start the server. The Sequelize models are synced to the MySQL databse.

The API GET routes in Insomnia Core for categories, products, or tags, the data for each of these routes is displayed in a formated JSON object.

The API POST, PUT, and DELETE routes in Insomnia Core will create, update and delete data in the database.

## Installation
Create database by entering these commands in mysql:

*Note: drops database if exists (ecommerce_db)
```mysql
source schema.sql
```

Enter these commands to start the application:
```bash
npm i
npm run seed
npm start
```

[MySQL2](https://www.npmjs.com/package/mysql)

[Sequelize](https://www.npmjs.com/package/sequelize)

[dotenv](https://www.npmjs.com/package/dotenv) 

## Walkthrough Video
https://watch.screencastify.com/v/V4gM4vHcdh5Z8CfJ6wMM

![walkthrough](https://github.com/jessicamcg/e-commerce-backend/blob/main/assets/e-commerce-backend%20walkthrough.gif)