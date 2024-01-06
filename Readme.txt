
Project Name: art_project
Version: 1.0.0

Description:
This project is a Blogging application designed for handling and managing blog posts.
It includes features for user authentication, utilizing technologies like JWT (JsonWebToken) for secure user sessions, and bcryptjs for password hashing. 
The project is connected with Mongodb for database. 

When project start it shows the landing  page  , we can login and register by options available in header  ,Blog list page is accessible only after user logs in  ,
You can create blog only after login  , also  can Edit and Delete by options available in blogs  ,you can alos search  blog by Title or Author's name  , 
Only 9 items are render through backend on blog list page , if more then 9 blogs are added pagination will automatically start.

Steps to install and run project :

1-> Clone the repository: git clone 
2-> Create env file same as env.example in both server and frontend
3-> Navigate to the project directory and install dependecy for backend: npm install --legacy-peer 
4-> Start the server using : npm start
5-> Navigate to the project frontend: cd frontend 
6-> Now install dependecy for frontend: npm install --legacy-peer 
7-> Run the frontend app using : npm start

Backend Dependencies:
axios: ^1.6.2 - HTTP client for making requests.
bcryptjs: ^2.4.3 - Library for hashing passwords.
body-parser: ^1.20.1 - Middleware to parse HTTP request body.
cors: ^2.8.5 - Middleware for handling Cross-Origin Resource Sharing.
dotenv: ^16.3.1 - Module to load environment variables from a .env file.
express: ^4.18.2 - Web application framework for Node.js.
http-status: ^1.7.3 - HTTP status codes.
jsonwebtoken: ^9.0.2 - Implementation of JSON Web Tokens for user authentication.
moment: ^2.29.4 - Library for handling dates and times.
mongodb: ^4.12.1 - Official MongoDB driver for Node.js.
mongoose: ^6.7.3 - MongoDB object modeling for Node.js.
mysql: ^2.18.1 - MySQL database driver for Node.js.
nodemon: ^2.0.22 - Utility that monitors for changes and automatically restarts the server.
passport: ^0.7.0 - Authentication middleware.
passport-jwt: ^4.0.1 - Passport strategy for authenticating with JSON Web Tokens.
util: ^0.12.5 - Utility functions.
validator: ^13.11.0 - Library for data validation.

Frontend Dependencies : 
axios: ^1.6.2 - HTTP client for making requests.
bootstrap: ^5.2.2 - CSS framework.
clsx: ^2.0.0 - Library for conditionally joining class names.
dayjs: ^1.11.10 - Library for handling dates and times.
lodash: ^4.17.21 - Utility library.
react: ^18.2.0 - JavaScript library for building user interfaces.
react-dom: ^18.2.0 - DOM-specific methods for React.
react-helmet-async: ^2.0.1 - Asynchronous version of React Helmet for managing document head.
react-hook-form: ^7.48.2 - Library for managing forms in React.
react-router-dom: ^6.20.0 - Declarative routing for React.js.
react-scripts: 5.0.1 - Configuration and scripts for Create React App.
react-toastify: ^9.1.3 - Notification library for React.
typescript: ^4.9.5 - Superset of JavaScript with static typing.
web-vitals: ^2.1.4 - Library for measuring web performance metrics.



Author:
Aishwarya Raj Tyagi
#art

