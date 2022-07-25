# Express + Sequelize

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

The initial user data take from `users.json` file. You should be able to edit all fields in json file apart from `index` and `id`.
Instead of working with a files - create a users table in SQL database.

To do this use `sequelize` and `sequelize-cli` libraries.
- Create a new table by using migrations.
- Add the users data from json file to database by using seeders.
- Create a user model in a project
- Use user model in API route handlers to work with a user data.

Extra tasks:
 - Add `cors` middleware
 - Block delete and update routes and allow only administrator to do it.
 - Provide the API docs in Swagger or as Postman collection.
