# Online Bookstore Application

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)

## Introduction

The Online Bookstore Application is a web-based platform designed to facilitate the purchase of books online. Users can browse a wide range of books, view book details, add them to their cart, and complete the purchase process seamlessly.

## Features
- User authentication and registration.
- Browse books by category and author.
- Search for books using keywords.
- View detailed information about each book, including its title, author, price, and description.
- Add books to a shopping cart.
- Manage the shopping cart by updating quantities and removing items.
- Complete the purchase process, including providing shipping and payment information.

## Technologies
- Frontend:

  - HTML, CSS, JavaScript
  - React.js for the user interface
  - Redux for state management
 
- Backend:

  - Node.js
  - Express.js for the server
  - MongoDB for the database
  - JWT for authentication

## Installation
1. Clone the repository:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd online-bookstore
```

3. Install dependencies for the frontend:

```bash
cd client
npm install
```

4. Install dependencies for the backend:

```bash
cd ..
cd server
npm install
```

5. Set up the database:
     - Install MongoDB and configure the connection in `server/config/config.js`.
6. Start the application:

```bash
cd ..
npm run dev
```

## Usage
- To run the application
```bash
npm start
```
- Access the application in a web browser at [http://localhost:3000](http://localhost:3000).
- Use the application to browse books, add them to your cart, and complete the checkout process.

## Contributing
Welcome contributions from the community. If you'd like to contribute to this project, please follow these guidelines:

- Fork the repository and create a new branch for your contribution.
- Make your changes and ensure the code is well-documented and formatted.
- Open a pull request explaining your changes and the problem they solve.
