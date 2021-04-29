This is a project for the Thinkful Software Engineering curriculum.

The purpose of this assignment is to practice integrating remote databases
with the backend of an application using knex for PostgreSQL migrations and seeding.

This project has a pre-built frontend that does not work properly when
deployed because of a connection limit imposed by elephantsql.com.

To test this project fully using its frontend, both this repository
and its frontend counterpart at https://github.com/djdenney/frontend-we-love-movies
need to be deployed locally.

The project backend itself can be tested using its deployment located on vercel/github
using the following paths:

/movies *GET all movie data*
/movies?is_showing=true *GET all movies currently showing*
/movies/:movieId (1, 2, 3, etc.) *GET data for a specific movie, identified by id*
/movies/:movieId/theaters *GET which theaters are currently showing this movie*
/movie/:movieId/reviews *GET reviews for selected movie*
/reviews/:reviewId (1, 2, 3, etc.) *DELETE or UPDATE the content of 1 review*
/theaters *GET all theaters and movies playing at each theater*

