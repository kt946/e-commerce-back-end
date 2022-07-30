# E-commerce Back End
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/licenses/MIT)

## Description

For this project, I built the back end of an e-commerce website using my knowledge of Object-Relational Mapping (ORM), the Sequelize package, JavaScript, and SQL, as well as tools such as Node.js, Mysql2, Express, Dotenv, and Insomnia. The back end of the application allows a developer to manage a business's database efficiently through the use of Sequelize, which makes it easier to create and update databases and tables by converting JavaScript to SQL queries. Developing the back end helped me to understand object-oriented principles and apply them to SQL databases and tables with the Sequelize package.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Links](#links)

## Installation

To install this application:
- Clone the application's repository and place it into a local directory on your computer.
- Ensure that your computer has node.js installed. To check the current version installed, type:
```
    node -v
```
- Ensure that MySQL and Insomnia are installed on your computer.
- Open a command-line interface (VS Code, Git Bash, etc.) and navigate to the directory containing the application's server.js.
- In the command-line, to download the application's dependencies, type: 
```
    npm install
```
- The dependencies include:
  - express
  - mysql2
  - sequelize
  - dotenv
- Create an .env file in the root directory and input the following into the file while using your own username and password:
```
    DB_NAME='ecommerce_db'
    DB_USER='your_username'
    DB_PW='your_password'
```
- Type the following command into the terminal. When prompted, input the password for the MySQL Shell to connect to the database.
```
    mysql -u root -p 
```
- To create the database, type: 
```
    source db/schema.sql
```
- To exit the MySQL Shell, type:
```
    quit
```
- Next, to seed data into the database, type:
```
    npm run seed
```

## Usage

- To start the server, type the following command and the message "App listening on port 3001!" will appear in the terminal.
```
npm start
```
- While the server is running, open Insomnia, create a new request of any type (GET, POST, PUT, DELETE) and set the address to 'http://localhost:3001/api' with either /categories, /products, or /tags as the endpoint.
- Use the different requests to implement Create, Read, Update, and Delete (CRUD) operations to the database.
- See the link for the walkthrough of the application:

    [Link to walkthrough video: E-commerce Back End](https://watch.screencastify.com/v/NkoELdgsoMD2tdhjJw38)

## Credits

- [kt946](https://github.com/kt946)

## License

This application is covered under the [MIT](https://opensource.org/licenses/MIT) License.

## Links

- [Link to GitHub repository](https://github.com/kt946/e-commerce-back-end)
