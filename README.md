# E-Commerce Back End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description 
Node.js application allowing users to create and manage an e-commerce database
## Table Of Contents
* [Installation](#installation)
* [Videos](#videos)
* [Usage](#usage)
* [Built Using](#built)
* [License](#license)
* [Contribution](#contribution)
* [Questions](#questions)

## Installation
  * To install locally, clone the respository
    * ``cd`` to the cloned directory and ru ``npm install`` to download dependencies
    * You will need to create your own ``.env`` file with local database credentails ``DB_NAME, DB_USER, DB_PW``
    * run ``node server.js`` to initialize the server
      * localhost:3001 will be utilized, and page can be tested in a program such as insomnia or postman

## Videos
  * [Setup db, seeding db, and initializing server](https://drive.google.com/file/d/1xdjw_Kn_W_es9Cvpcbz2eW5zSHIHUArR/view?usp=sharing)
  * [Show usage using Insomnia](https://drive.google.com/file/d/1HYamFcjgxyuQ2hVMflB-oz1P9zxAt6_y/view?usp=sharing)

## Usage (Back End)
  * Endpoints available:
    * Categories
      * GET all (../ api/categories/)
      * GET by id (../ api/categories/:id)
      * CREATE (../api/categories/) ``JSON body`` requires key ``category_name``
      * PUT (update) by id (../ api/categories/:id) ``JSON body`` requires key ``category_name``
      * DELETE (destroy) by id (../ api/categories/:id)
    * Products
      * GET all (../ api/products/)
      * GET by id (../ api/products/:id)
      * CREATE (../api/products/) ``JSON body`` require keys ``product_name, price, stock, tagIds`` and optional ``category_id``
      * PUT (update) by id (../ api/products/:id) ``JSON body`` requires key ``tagIds``
      * DELETE (destroy) by id (../ api/products/:id)
    * Tags
      * GET all (../ api/tags/)
      * GET by id (../ api/tags/:id)
      * CREATE (../api/tags/) ``JSON body`` requires key ``tag_name``
      * PUT (update) by id (../ api/tags/:id) ``JSON body`` requires key ``tag_name``
      * DELETE (destroy) by id (../ api/tags/:id)

## Built
  * [Node.js](https://nodejs.org/en/)
  * [dotenv](https://www.npmjs.com/package/dotenv)
  * [Express.js](https://expressjs.com/)
  * [Sequelize.js](https://sequelize.org/)
  * [mysql2](https://www.npmjs.com/package/mysql2)

## License
This application is covered under the [MIT](https://opensource.org/licenses/MIT) license.

## Contribution
  * There is no contribution required for this project

## Tests
  * There are no tests for this project

## Questions
Please feel free to contact me regarding any further questions:
* [GitHub Profile](https://github.com/PrimalOrB)
* [Email Me](mailto://primalorb@gmail.com)
