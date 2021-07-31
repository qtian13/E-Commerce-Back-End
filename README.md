# E-Commerce Back End
This project is to build the back end for an e-commerce site by modifying starter code. It configures a working Express.js API to use Sequelize to interact with a MySQL database.

## Table of Contents
* [Installation](#installation)
* [Built With](#built-with)
* [Features](#features)
* [Demo Video](#demo-video)
* [Author](#author)
* [Questions](#questions)
* [Acknowledgments](#acknowledgments)

## Installation
1. Log in to mysql to create the database
2. Create a file named .env in the root directory and store your own local varialbes like DB_NAME, DB_USER, DB_PASSWORD
3. Run the following command to install packages required, seeds database and start the application
```bash
git clone https://github.com/qtian13/E-Commerce-Back-End.git
npm init -y
npm i
npm run seed
npm run watch
```
## Built With
* [JavaScript](https://www.javascript.com/)
* [NodeJS](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* [mysql](https://www.mysql.com/)

## Features
* It provides a back end for E-commerce website that uses the latest technologies
* With a functional Express.js API, when user add their database name, MySQL username, and MySQL password to an environment variable file, they are able to connect to a database using Sequelize
* When user enter schema and seed commands, a development database is created and is seeded with test data
* When user enter the command to invoke the application, the server is started and the Sequelize models are synced to the MySQL database
* When user open API GET routes in Insomnia Core for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON
* When user test API POST, PUT, and DELETE routes in Insomnia Core, they are able to successfully create, update, and delete data in their database
* When user delete a certain category, the data of that category and all the products belongs to that category would also be deleted

## Demo Video
Demo Video: [https://drive.google.com/file/d/1aErAjk8DKeQts1f4_4766ovCLfzKdvvk/view](https://drive.google.com/file/d/1aErAjk8DKeQts1f4_4766ovCLfzKdvvk/view)

## Author
Qiushuang Tian
- [Link to Portfolio Site](https://qtian13.github.io/myPortfolio/)
- [Link to Github](https://github.com/qtian13)
- [Link to LinkedIn](https://www.linkedin.com/in/qiushuang-tian-a9754248/)

## Questions
Please reach me out with additional questions!

Emails: qiushuang.tian@gmail.com

## Acknowledgments
- [Berkeley Coding Boot Camp](https://bootcamp.berkeley.edu/coding/) provided mock up image and starter code






