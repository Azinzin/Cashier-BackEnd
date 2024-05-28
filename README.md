# Cafe Website Backend

A backend for a cafe website built with Node.js, Express, MySQL, and Sequelize. This project provides an API to manage the menu, orders, and customer information for the cafe.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Features

- Manage cafe menu (add, update, delete, view menu)
- Manage orders (create order, update order status, view orders)
- Manage customer information (add, update, delete, view customers)

## Installation

1. Clone this repository
    ```bash
    git clone https://github.com/username/cafe-website-backend.git
    cd cafe-website-backend
    ```

2. Install dependencies
    ```bash
    npm install
    ```

3. Create a `.env` file and configure it according to your environment
    ```plaintext
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=yourpassword
    DB_NAME=cafe_db
    ```

4. Run database migrations
    ```bash
    npx sequelize-cli db:migrate
    ```

## Configuration

Ensure you have configured the `.env` file correctly to connect the application to your MySQL database.

## Usage

To start the server, use the following command:
```bash
npm start
