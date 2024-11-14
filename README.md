# 🎥 CineMaster API

A RESTful API for managing a movie database built with Go and Gorilla Mux. This project features full CRUD (Create, Read, Update, Delete) functionality, allowing users to efficiently handle movie records, including details like the title, ISBN, and director information.

## 🚀 Features

- **Fetch All Movies**: Retrieve the complete list of movies.
- **Get a Movie by ID**: Access specific movie details using the movie's ID.
- **Add a New Movie**: Create new movie entries with dynamic IDs.
- **Update an Existing Movie**: Modify details of a movie by its ID.
- **Delete a Movie**: Remove movie records from the database.

## 🛠️ Built With

- [Go](https://golang.org/): Backend programming language
- [Gorilla Mux](https://github.com/gorilla/mux): HTTP request router and dispatcher

## 📚 API Endpoints

| Method | Endpoint           | Description             |
| ------ | ------------------ | ----------------------- |
| GET    | `/movies`          | Get all movies          |
| GET    | `/movies/{id}`     | Get a single movie by ID|
| POST   | `/movies`          | Add a new movie         |
| PUT    | `/movies/{id}`     | Update an existing movie|
| DELETE | `/movies/{id}`     | Delete a movie by ID    |

## 🧩 Example Movie Data

```json
{
    "id": "001",
    "isbn": "438227",
    "title": "Pulp fiction",
    "director": {
        "firstN": "Quentin",
        "lastN": "Tarantino"
    }
}
```
## 🏃‍♂️ Getting Started
  1. Clone repository
     
`git clone https://github.com/yourusername/cinemaster-api.git`

 1. Clone repository
     
`cd cinemaster-api
`
2. Navigate to the project directory
     
`go run main.go
`
3. Run the server
     
`go run main.go
`
4. Access the API Open your browser or API client (like Postman) and go to:
`http://localhost:8000/movies
`

