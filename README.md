# Day 4: Creating a model or database table

You have your database connected now but need a table to hold certain data. You are creating an API for a bookstore. Each book has to be identified uniquely and possesses properties that help in proper categorization. Decide what the properties or fields of this Book Model will be and create a Database Table for it.

## Setup
NOTE: We'll be using "MySQL" for this setup
- Navigate to the root of this repo.
- Open the 'main.go' file
- Update the following variables with your preferred database details
    - DB_USER
	- DB_PASS
	- DB_DATABASE
- Run the command ```go run ./main.go``` to start the server.
- Visit the url http://127.0.0.1:3000 to check if the connection was successful and the tables were created