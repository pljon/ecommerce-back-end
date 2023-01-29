# E-Commerce Back End

## Description
This is the back-end of an e-commerce website using Express.js API. It contains a MySQL database which is connected using Sequelize, with a development database created and seeded with test data. The server is started and Sequelize models are synced to the MySQL database. The API routes for GET, POST, PUT, and DELETE are tested and successfully able to display, create, update, and delete data in the database.

## Installation

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

* Run the commands `npm i` and `npm dotenv` to install the necessary dependencies

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

* Run the command `source db/schema.sql` once logged into your MySQL database.

* Run `npm run seed` to seed data to your database so that you can test your routes.

## Demos

The following animation shows how to create the database and how to seed it with data via command-line in VSCode:

![schema-seed-demo](./demo/13-run-schema-seeds.gif)

The following animation shows the application's category routes (creating, reading, updating, deleting) in Insomnia:

![category-routes-demo](./demo/13-category-route-demo.gif)

The following animation shows the application's product routes (creating, reading, updating, deleting) in Insomnia:

![product-routes-demo](./demo/13-product-route-demo.gif)

The following animation shows the application's tag routes (creating, reading, updating, deleting) in Insomnia:

![tag-routes-demo](./demo/13-tag-routes-demo.gif)