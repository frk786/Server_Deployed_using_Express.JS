# INTRODUCTION:
A server deployed using Express.js is a backend application running on a web server, built using the Express.js framework on top of Node.js. It can handle HTTP requests, process data, interact with databases, and serve APIs or web pages.

Key Features of an Express.js Server

✅ Lightweight & Fast – Minimalistic framework with efficient performance.

✅ RESTful API Support – Ideal for building APIs for web and mobile apps.

✅ Middleware Support – Enables functionalities like authentication, logging, and request processing.

✅ Scalability – Can handle multiple concurrent requests efficiently.

# INITIALIZATION OF SERVER:

Creates a package.json File. The package.json file is essential for managing dependencies, scripts, and metadata of a Node.js project.
     
     - npm init -y 

    

# IMPORTING EXPRESS MODULE:

This command npm install express (or npm i express) is used to install the Express.js framework in a Node.js project.
    
     - npm install express 

# SETTING A SERVER (STEPS INCLUDE):

## 1. Importing Express:

This imports the Express module using ES6 syntax. By default, Node.js uses CommonJS (require). To use import, you need to:
Add "type": "module" in your package.json file.

     - import express from "express";

## 2.  Creating an Express App:

Initializes an Express application. The app object will handle routing and server logic.

     - const app = express();

## 3.  Defining the Port:

The server will run on port 3000. You can change this to any available port.

    - const port = 3000;

  
## 4. Defining a Route

app.get("/"): Defines a route for GET requests to the root URL ("/"). (req, res) => {...}: Callback function that runs when the route is accessed.
res.send(""): Sends a simple HTML response.


## 5. Starting the Server

app.listen(port, callback): Starts the Express server and listens on the specified port. The callback function runs when the server starts and logs a message.

## 5. Testing the Server

By exucuting all the code correctly, we can run our server on a browser as a localhost on port:3000



# CONCLUSION:

By following the above all steps, we will be able to create a server listening on a specified port using Express.JS. This setup is a foundation for building REST APIs and web applications.
