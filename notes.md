# Notes

- 7.1 Assignment
    - Update the POST /api/chirps endpoint to only allow users to create chirps if they are authenticated. 
    - When they do create a chirp, the chirp should be associated with the user who created it.
    - Add a new author_id field to your chirps and use it to store the user's ID.
    - Make sure that the GET /api/chirps endpoints return the author_id field as well.


- 7.4 Assignment
    - Add a new DELETE /api/chirps/{chirpID} route to your server that deletes a chirp from the database.
    - This is an authenticated endpoint, so be sure to check the token in the header. 
    - Only allow the deletion of a chirp if the user is the author of the chirp.
    - If they aren't return a 403 status code.
    - If the chirp is deleted successfully, return a 200 status code.
