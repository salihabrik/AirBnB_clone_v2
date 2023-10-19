
# AirBnB Clone - Web Framework

This project involves building a web application using the Flask web framework. The goal is to create a simple web application that listens on a specified port and handles various routes to display different content.

![alt text](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step3.png)

## Learning Objectives

By the end of this project, you will have gained a deep understanding of the following concepts:

- What is a Web Framework
- How to build a web framework with Flask
- Defining routes in Flask
- Handling variables in a route
- Working with templates
- Creating dynamic templates with loops and conditions
- Displaying data from a MySQL database
- Developing Flask routes and templates

Welcome to the Airbnb Clone Project! In this project, we will walk through the process of building a simplified clone of the Airbnb website. This project is structured into several steps, each of which covers fundamental concepts of higher-level programming and web development.

## Project Overview

The goal of this project is to deploy a web application that replicates some features of the Airbnb website. By the end of the first year of development, we will have a fully functioning web application composed of the following components:

1. **The Console**
   - Create a command interpreter to manage data without a visual interface.
   - Implement data manipulation functions, such as create, update, and destroy objects.
   - Store and persist objects to a JSON file.
   - Use this console to validate the storage engine.

2. **Web Static**
   - Learn HTML and CSS to create the static components of the website.
   - Develop the HTML structure of the application.
   - Create templates for each object to be displayed on the website.

3. **MySQL Storage**
   - Replace the file-based storage with a database storage system, such as MySQL.
   - Map data models to database tables using an Object-Relational Mapping (ORM) framework.

4. **Web Framework and Templating**
   - Create a web server in Python.
   - Make static HTML files dynamic by integrating data from files or the database.

5. **RESTful API**
   - Expose all objects through a JSON-based RESTful API.
   - Implement CRUD operations to manipulate objects via the API (Create, Read, Update, Delete).

6. **Web Dynamic**
   - Learn jQuery to enhance the dynamic behavior of the website.
   - Load objects from the client side using your custom RESTful API.

7. **Files and Directories**
   - Organize the project's structure into directories, including "models" and "tests."
   - Create a base model class to represent common attributes and methods for all models.
   - Implement a storage class for managing storage-related operations.

8. **Serialization and Deserialization**
   - Serialize Python objects into a format like JSON for storage.
   - Deserialize data from JSON to recreate Python objects.

9. **\*args and \*\*kwargs**
   - Utilize \*args for handling a variable number of anonymous arguments.
   - Use \*\*kwargs for managing named arguments in dictionary format.

## Why This Project?

This project is designed to provide you with hands-on experience in various aspects of web development, including building a web application, working with databases, creating APIs, and understanding storage concepts. By following the steps in this project, you'll gain a comprehensive understanding of web development and software engineering principles.

## Getting Started

To get started with this project, follow the steps mentioned in the project overview above. Each step links to a concept and provides guidance on what to learn and implement. Feel free to adapt the project to your own needs and explore additional features beyond the scope of this README.

## Contributing

If you're interested in contributing to this project or have suggestions for improvements, please feel free to open an issue or submit a pull request.


### Manual QA Review
It is your responsibility to request a review for this project from a peer before the project’s deadline. If no peers have reviewed, you should request a review from a TA or staff member.

## Tasks

### 0. Hello Flask!
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- You must use the option `strict_slashes=False` in your route definition.

### 1. HBNB
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- `/hbnb`: display "HBNB"
- You must use the option `strict_slashes=False` in your route definition.

### 2. C is fun!
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- `/hbnb`: display "HBNB"
- `/c/<text>`: display "C ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- You must use the option `strict_slashes=False` in your route definition.

### 3. Python is cool!
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- `/hbnb`: display "HBNB"
- `/c/<text>`: display "C ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- `/python/<text>`: display "Python ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- The default value of text is "is cool".
- You must use the option `strict_slashes=False` in your route definition.

### 4. Is it a number?
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- `/hbnb`: display "HBNB"
- `/c/<text>`: display "C ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- `/python/<text>`: display "Python ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- The default value of text is "is cool".
- `/number/<n>`: display "n is a number" only if n is an integer.
- You must use the option `strict_slashes=False` in your route definition.

### 5. Number template
- Write a script that starts a Flask web application.
- Your web application must be listening on 0.0.0.0, port 5000.
- Routes:
- `/`: display "Hello HBNB!"
- `/hbnb`: display "HBNB"
- `/c/<text>`: display "C ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- `/python/<text>`: display "Python ", followed by the value of the text variable (replace underscore `_` symbols with a space).
- The default value of text is "is cool".
- `/number/<n>`: display "n is a number" only if n is an integer.
- `/number_template/<n>`: display an HTML page only if n is an integer:
  - H1 tag: "Number: n" inside the tag BODY.
- You must use the option `strict_slashes=False` in your route definition.

## Authors

- [salihabrik, Se at Holberton School](https://github.com/salihabrik)
