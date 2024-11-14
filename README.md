# GoMovieHub-API

A RESTful API for managing a movie database built with Go and Gorilla Mux. This project features full CRUD functionality, allowing users to create, read, update, and delete movie records. Each movie entry includes a title, ISBN, and director details. The API includes:
🗂️ GET /movies: Fetch all movie records.
🎬 GET /movies/{id}: Retrieve a single movie by ID.
➕ POST /movies: Add a new movie to the database.
✏️ PUT /movies/{id}: Update an existing movie entry.
❌ DELETE /movies/{id}: Remove a movie from the database.
Built using Go for backend logic and the Gorilla Mux package for efficient request routing.
