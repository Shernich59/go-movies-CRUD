# go-Movie API

This is a simple RESTful API for managing movies, built using the Go programming language and Gorilla Mux router.

## Description

This project is a beginner-friendly introduction to building web APIs in Go. It demonstrates basic CRUD (Create, Read, Update, Delete) operations for managing movie resources.

## Features

- HTTP Server: Sets up a basic HTTP server to handle incoming requests.
- Routing: Defines routes to handle different URL paths.
- Request Handling: Parses form data and handles different HTTP methods (GET, POST, PUT, DELETE).
- Error Handling: Provides error responses for invalid requests.

### Function Details

#### `getMovies`
- **Description:** Retrieves a list of all movies.
- **HTTP Method:** GET
- **Route:** `/movies`

#### `getMovie`
- **Description:** Retrieves a single movie by its ID.
- **HTTP Method:** GET
- **Route:** `/movies/{id}`

#### `createMovie`
- **Description:** Creates a new movie.
- **HTTP Method:** POST
- **Route:** `/movies`

#### `updateMovie`
- **Description:** Updates an existing movie.
- **HTTP Method:** PUT
- **Route:** `/movies/{id}`

#### `deleteMovie`
- **Description:** Deletes a movie by its ID.
- **HTTP Method:** DELETE
- **Route:** `/movies/{id}`

## Usage
1. Start the server by running the following command:

""" 
go build
go run main.go

"""

2. Interact with the API using tools like cURL or Postman.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License.

## Acknowledgements
- [Gorilla Mux](https://github.com/gorilla/mux) for routing
