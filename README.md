# E-commerce Back End
An ExpressJS application that utilises npm module sequelize and pg to allow users to interface with a PostgreSQL database via a RESTful API.

A demonstration of this application can be viewed [here](https://youtu.be/iHLjqjnwqvc).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)
- [Questions](#questions)

## Installation

To run this application, ensure you have `PostgreSQL 16.4`, `NodeJS`, and `npm` or `bun` installed.

Follow these step-by-step instructions to get a development environment running.

```shell
# Clone this repo
git clone https://github.com/kevinvongmany/e-commerce-backend.git

# Navigate to the project directory
cd e-commerce-backend

# Install npm environment
npm install

# OR Install bun environment
bun i

# Copy the .env.EXAMPLE and rename to .env and populate your user credentials for your PostgreSQL environment
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''

```
  

## Usage
Instructions on how to run this application within npm or bun. Ensure you are navigated to the project directory within terminal/console.

```shell
# Create your PostgreSQL database
psql -U postgres -f db/schema.sql # enter in your password when prompted

# Seed your data
npm run seed

# npm
npm run start

# bun
bun run start
```

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## Contribution
Guidelines for contributing to the project.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Questions

If you have any questions you can find me on GitHub here: [kevinvongmany](https://github.com/kevinvongmany)
  
You can also contact me via email here: [kevin.vongmany@gmail.com](kevin.vongmany@gmail.com)
