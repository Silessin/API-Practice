# Important API Queries for Music

This document outlines the most important API queries using songs as an example

## API Endpoints

1. **Get All Songs**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs`
   - **Description:** Retrieves a list of all songs in the database.

2. **Get Song by ID**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs/:id`
   - **Description:** Retrieves details of a specific song using its unique ID.

3. **Add a New Song**
   - **Method:** `POST`
   - **Endpoint:** `/api/songs`
   - **Description:** Adds a new song to the database. Requires `title`, `artist`, and optional fields (`album`, `genre`, `year`).

4. **Update a Song**
   - **Method:** `PUT`
   - **Endpoint:** `/api/songs/:id`
   - **Description:** Updates an existing song's details using its ID.

5. **Delete a Song**
   - **Method:** `DELETE`
   - **Endpoint:** `/api/songs/:id`
   - **Description:** Deletes a song from the database based on its ID.

6. **Get Songs by Artist**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs?artist={artistName}`
   - **Description:** Retrieves all songs by a specific artist.

7. **Search Songs by Title**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs?title={title}`
   - **Description:** Searches for songs with titles matching the specified query.

8. **Get Songs by Genre**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs?genre={genre}`
   - **Description:** Retrieves all songs that belong to a specific genre.

9. **Get Songs Released in a Specific Year**
   - **Method:** `GET`
   - **Endpoint:** `/api/songs?year={year}`
   - **Description:** Retrieves all songs released in the specified year.

10. **Get Total Number of Songs**
    - **Method:** `GET`
    - **Endpoint:** `/api/songs/count`
    - **Description:** Returns the total count of songs in the database.

