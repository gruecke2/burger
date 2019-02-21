# Burger App
A handlebars and express app with database connectivity.

## About
A simple MySQL MVC based web app running on Express and NodeJS for backend, handlebars styled with Bootstrap for frontend.

## How to use
Enter a burger, or click the devour button to change the state of the "devoured" table in the database to true. Devoured burgers are displayed on the right (bottom for mobile), while currently "available" burgers are on the left.

## Tech Used

The Burger app uses a variety of node packages and other tech to work:

* [mysql](https://www.npmjs.com/package/mysql) - mysql implementation into node
* node.js - Runtime environment for the JavaScript
* [express](https://www.npmjs.com/package/express) - express server for backend
* [handlebars](https://www.npmjs.com/package/handlebars) - template html with dynamic elements
* [JawsDB MySQL](https://elements.heroku.com/addons/jawsdb) - Heroku addon to run the database live



## Todos
- More styling
- Next iteration will use sequelize for easier SQL queries
- Ability to edit or delete entries
- User "customer" table to be related to the burgers table
