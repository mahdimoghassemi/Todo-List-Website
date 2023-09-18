# Todo List Website

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

## Introduction

This is a simple yet effective Todo List web application designed to help users manage their tasks efficiently. It provides a user-friendly interface for adding, editing, marking tasks as done or undone, and deleting tasks.

## Features

- User authentication and session management
- Add new tasks with titles, start dates, and end dates
- Edit existing tasks
- Mark tasks as done or undone
- Delete tasks
- View tasks in a clear tabular format
- Responsive design for desktop and mobile devices

## Screenshots

_Insert screenshots or demo GIFs here to showcase the application's interface._

## Getting Started


### Prerequisites

- [Web server](https://www.apachefriends.org/index.html) (e.g., XAMPP, WAMP)
- [MySQL Database](https://www.mysql.com/)
- [PHP](https://www.php.net/)

### Installation

1. Clone the repository to your local machine:

   
bash
   git clone https://github.com/your-username/todo-list-website.git
   

2. Set up your web server (e.g., Apache) and MySQL database. Ensure PHP is configured.

3. Create a new MySQL database and import the provided SQL schema from database.sql.

4. Configure your database connection in config.php:

   
php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'your-username');
   define('DB_PASSWORD', 'your-password');
   define('DB_NAME', 'your-database-name');
   

5. Start your web server and navigate to the project directory.

6. Open the application in your web browser.

## Usage

1. Register for an account or log in if you already have one.

2. Use the interface to add new tasks, edit existing tasks, mark tasks as done or undone, and delete tasks.

3. Enjoy managing your tasks efficiently with this Todo List application!

