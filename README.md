# Arrays

## Homework

### The task description

The third-party service sends to us the list of new emplyers. You can find them in users.json file in this repo.

We need detect only active users and create a `json file` with a new structure for them.
```json
[
  {
    "id": "userId",
    "name": "fullname",
    "company": "Apriorit",
    "email": "mymail@site.com",
    "age": "29",
  },
  ...
]
```

1. Find all active users in json structure.
2. For the active users change the company name to `Apriorit`.
3. Create a new json structure for them.
4. For the new Atriorit users, find the users with the age less than 25 years old and add extra parameter to it's data {"isStudent:": "true" }.
5. Print the user emails to console that have `isStudent` parameter.
6. Creta a apriorit-users.json file in terminal. Add all apriorit users to this file.

The script should generate apriorit-users.json file automatically.

