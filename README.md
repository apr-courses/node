# Express

## Homework

### The task description

Create a rest API to manage all the users in the app. Use nodejs `express` library for this. 

The API routes should do the following actions:
 - get all users
 - get one user by id
 - update one user
 - update all users
 - delete one user
 - create a new user
 
Use GET, POST, PUT, PATCH, DELETE methods to do this.

The initial user data take from `users.json` file
After any changes - update this file. Every API request should take a new data from json file.

You shpould be able to edit all fields in json file apart from `index` and `id`.

Extra tasks:
 - Add `cors` middleware
 - Block delete and update routes and allow only administrator to do it.
 - Provide the API docs in Swagger or as Postman collection.
