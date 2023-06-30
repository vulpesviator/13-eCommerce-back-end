# eCommerce Back-End

## Description

This project uses a MySQL database and express.js API to create a back-end inventory management system for an eCommerce site. The database cross-references products with categories and tags to better filter and describes the product. It allows these values to be easily updated and configured.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To run this application locally, clone or download the repo which contains the necessary sql schema and js files.

## Usage

[Video Walkthrough of the eCommerce Back-End](https://drive.google.com/file/d/1U2EutwXn3o-vG4H8U1wOwNXP1NzlEzKh/view?usp=sharing)

![eCommerce Back-End](./assets/img.gif)

1. Begin by logging into your local MySQL environment with `mysql -u root -p`. You will be prompted to enter your password for your MySQL instance.
2. Next locate the schema source for your database by entering `source db/schema.sql` or the path to the schema.sql file in your directory. This should respond with the database being created. If created successfully you can exit the MySQL interface with `exit`
3. Next you will want to run the seeds with `npm run seed`. This will fill in the tables of the database with sample information.
4. Then you can start the server by typing `npm run start`.


## Contributing

- Module 13 Mini-Project: Travel Planner


## License
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  The MIT License

## Tests

Test can be run from Insomnia or other API client to test GET, POST, PUT, and DELETE methods for products, categories, or tags. 

## Questions

Created by [vulpesviator](http://github.com/vulpesviator)

[Contact Me](vulpesviator@gmail.com)

Copyright (c) [2023] [Travis Hoffman]