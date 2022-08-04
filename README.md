# restAPI-practice

Rest API dev enviorment created using a combination of Node.js, Express & MongoDB to test the creating, deleting, and updated a subscriber database. All functions and packages including test enviroment were built and created from within VS Code using npm i and npm i --save-dev dotenv nodemon to install all the necessary npm packages. dotenv allows the user to pull in enviorment variables from a .env file and nodemon allows the user to refresh the server everytime changes are made without having to mannually end it and restart it.

A self created script from within the package.json file allows the user to run nodemon from which you can then create your own sever name as a javascript file in order to access it on your local host port once activated.

An extension used for VS Code called REST Client allows users to send HTTP request to the server and see the response directley in VS Code just so long as a .rest file is created. It is best to place this file within the same directory as your routes file for organizational purposes. Each new request made must be sperated with three pound symbols (###) in order to be able to be read by the extension.