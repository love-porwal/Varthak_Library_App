Varthak- Library App Assignment 

Manage and Try our Varthak for an added boost to your business!

## Table of Contents
- [Introduction](#introduction)
- [Project Demo](#project-demo)
- [Features](#Features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
  - [Authentication](#authentication)
  - [Routes](#routes)

## Introduction
This library app project is a Node.js application built with TypeScript and Express, featuring user authentication, 
role-based access control, and the ability to manage and view books, with support for logging incoming requests using Winston.

## Project Demo
https://drive.google.com/file/d/1kc5m0A_Wvf8G88-nUCEX0lFfrHkQ_bw8/view?usp=sharing
  
## Features

- User registration and JWT authentication for login.
- Book management, including the ability to add, retrieve, and filter books by book createdAt timeline.
- role based access control after secure logging.
  
## Tech Stack

- **Node.js**: A JavaScript runtime for server-side development.
- **Typescript**: Programming language.
- **Express.js**: A web application framework for Node.js.
- **MongoDB**: A NoSQL database for storing data.
- **JWT**: JSON Web Tokens for authentication.
- **Other Dependencies**: Various Node.js libraries and modules.


## Getting Started

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/love-porwal/Varthak_Library_App.git
   
2. Navigate to the project directory:
   ```
   cd Varthak_Library_App
   npm init -y
   ```
   
3. Install dependencies:
   ```
   npm install 
   ```

4. Application Start
   ```
   npm start
   ```


## Usage
### Authentication
To use protected routes, you must authenticate by obtaining a JWT token. Use the /auth/login route to log in and get the token.


## Routes
### User Routes
```
User Registration: POST /auth/signup
User Login: POST /auth/login
```
### Book Routes
```
Create a Book: POST /books
Read a Book: GET /books
Read all Existing Books: GET /books/all
```
