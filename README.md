# Movie API

This is a RESTful API for managing movies and characters. It allows you to create, update, delete, and retrieve information about movies and characters. The API also supports the assignment of characters to movies and retrieving characters from a movie.

# API Endpoints

## Movies
GET /api/movies – Retrieve all movies.
GET /api/movies/{id} – Retrieve a movie by its ID.
POST /api/movies – Create a new movie.
PUT /api/movies/{id} – Update a movie.
DELETE /api/movies/{id} – Delete a movie.
POST /api/movies/{movieId}/characters – Assign characters to a movie.
GET /api/movies/{movieId}/characters – Get the characters of a movie.
## Characters
GET /api/characters – Retrieve all characters.
GET /api/characters/{id} – Retrieve a character by its ID.
POST /api/characters – Create a new character.
PUT /api/characters/{id} – Update a character.
DELETE /api/characters/{id} – Delete a character.
GET /api/characters/{characterId}/movies – Get the movies that a character appears in.