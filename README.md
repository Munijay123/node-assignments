# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/node-assignment/create-react-app).

## Available Scripts

In the project directory, you can run:

First, make sure you have MongoDB running locally on your machine (default port 27017).

Install the necessary Node.js packages by running:

### npm install
Then, start the server in development mode by running:

### npm run start
The server will run at:

### http://localhost:3000
3. REST API Endpoints
You can make HTTP requests to these endpoints:

### GET /load

Loads the first 10 users from JSONPlaceholder, including their posts and comments.

Stores them into MongoDB.

Returns an empty response with HTTP status 200 on success.

### GET /users/:userId

Fetches a single user by their userId.

Returns the user object with their posts, and each post with its comments.

If the user doesn’t exist, returns a 404 error.

### PUT /users

Adds a new user to the database.

You must send the full user object as JSON in the request body.

If a user with the same id already exists, returns a 409 Conflict error.

On success, returns HTTP 201 Created with a Location header showing the new user URL.

### DELETE /users

Deletes all users (and their posts and comments) from the database.

Returns HTTP 200 on success.

### DELETE /users/:userId

Deletes a specific user by their userId.

If the user doesn’t exist, returns a 404 error.

Returns HTTP 200 on success.

4. Development Notes
The project uses TypeScript, so all requests and responses are strongly typed.

The server uses Node.js built-in HTTP module (no Express).

You run the server with ts-node-dev which automatically reloads on code changes.

If ts-node-dev is not recognized, you need to install it:

### npm install --save-dev ts-node-dev

5. Troubleshooting
Make sure MongoDB is installed and running locally (mongod).

If ts-node-dev command fails, install it locally or globally.

Use tools like Postman or curl to test your REST endpoints.

6. Deployment
This server is designed for learning and local development.

For production, you’d need extra setup like environment variables, database credentials, security, etc.

### Summary
This README gives you all info to run, test, and understand the backend server project you created — from installation to API usage and troubleshooting.
 
 #   n o d e - a s s i g n m e n t s 
 
 #   n o d e - a s s i g n m e n t s 
 
 #   n o d e - a s s i g n m e n t s 
 
 
