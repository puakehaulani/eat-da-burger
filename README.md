# Eat Da Burger

<!-- [![Demo](https://img.youtube.com/vi/Y3fuixizR1I/0.jpg)](http://www.youtube.com/watch?v=Y3fuixizR1I) -->

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[Explore the docs](https://github.com/puakehaulani/eat_da_burger)

---

## Table of Contents

- [About the Project](#About-the-Project)
- [Usage](#Usage)
- [Getting Started](#Getting-Started)
  - [Installation](#Installation)
- [Testing](#Testing)
- [Contributing](#Contributing)
- [License](#License)
- [Questions](#Questions)

## About the Project

Eat da Burger is a restaurant app. Click Eat me to eat da burger, or click Order again to get one ready to devour! Enter in your own burgers to add to the menu. Sides coming soon!

This is basic full stack app built with a MySQL database, Express, Handlebars and a homemade ORM. The ORM can be extended to other menu items in the future.

## Usage

Enter your password into the password field (line 7) in config/connection.js

Run the following command in your terminal

    npm run watch

Then navigate to the following address in your browser

    localhost:3000

## Getting Started

To get started, follow these steps:

### Installation

Run the following command in your terminal

    npm i

Initilize database through mysql with the following command in your terminal

    mysql -u root -p
    source db/schema.sql
    source db/seeds.sql
    exit

## Testing

Run the following command in your terminal

    npm test

## Contributing

Contributions are welcome! Please create an issue or pull request with your input.

## License

This application is covered under the MIT license

## Questions

For any questions, please reach out to <puakehaulani@gmail.com>  
[Developer repo](http://github.com/puakehaulani)
