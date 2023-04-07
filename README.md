# BACKEND REST API (AUCTION)

[See frontend source code](https://github.com/Yooupy/rest-api-frontend)

This is a simple API for managing user accounts. It allows you to create new users, log in existing users, retrieve a list of all users, and perform other CRUD operations on individual users.

## Installation

To run this project on your machine, you will need to have Node.js and npm installed. Once you have those installed, follow these steps:

1. Clone the repository to your machine
2. Run `npm install` to install all required packages
3. Create(ask from admin) a `.env` file using the `env.example` file as a template
4. Run `npm start` to start server

## API endpoints

The API provides the following endpoints:

- POST /: create a new user
- POST /login: log in an existing user
- GET /: retrieve a list of all users
- GET /: id : retrieve a single user by ID
- PATCH /: id : update a single user by ID
- DELETE /: id : delete a single user by ID

To use the API, send HTTP requests to the appropriate endpoint using a tool like cURL, Postman, or a web browser. For example, to create a new user, you could send a POST request to http://localhost:3000/ with a JSON payload containing the user's name, email, and password:

```json
{
  "name": "John Doe",
  "email": "johndoe@example.com",
  "password": "secretpassword"
}
```

## Contributing

If you find a bug or would like to contribute to this project, please open an issue or pull request on GitHub.
