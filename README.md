Robust server structure: Advanced tips
Note: If downloading the assessment files to your local machine, make sure you're running Node v18 before you run npm install.

Check which version you are running: node -v
If needed, change the version to v18: nvm use v18
For additional help, review the "Learn your tools: Visual Studio Code" lesson in the "Welcome" module.

Instructions
Your task is to extend this API server, which stores "Notes" to enhance the error reporting functionality and add a read-only ratings resource.

Existing files
Use the existing data files located in src/data for the responses. Feel free to add or remove data from the files as necessary, but keep the same shape of the data.

Tasks
You should modify this server to meet the following requirements:

(AI-Assisted) /notes/:noteId/ratings returns all ratings for the note.
(AI-Assisted) /notes/:noteId/ratings/:ratingId returns the rating for the note with the specified rating ID, or 404 if the rating ID isn't associated with the note ID.
(Independent) /ratings returns all ratings.
(Independent) /ratings/:ratingId returns the rating the specified ID.
(Independent) Remove duplicate code by passing data on the response where appropriate.
(Independent) Return 405 and an error message for all the HTTP methods that aren't handled by the router.
