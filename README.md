# dummy-online-store
building an app that show that the enduser can interact with to use a online store

## Tech used
* express.js - router
* sequelize/ mysql
* node.js

## installion
make sure you have node.js already installed also you will need to install sequelize:

```
npm i sequelize
```
and mysql2

```
npm i mysql2
```

and dotenv

```
npm i dotenv
```

and express.js
```
npm i express
```


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```