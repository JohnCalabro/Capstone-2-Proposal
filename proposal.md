
Capston 2 Proposal:

For this application I am using React on the Front end and Node.js on the backend.  This project is primarily front end but will include some back end functionality specifically on the back end users can sign up for an account or login to favorite items, my own DB on postgres will keep track of users and their favorites. This will be a web application primarily designed for desktop. 

The goal of this project is to make a mini IMDB, it will allow visitors to type in a movie, TV show or video game or any type of media that is on the API through a text input. It will also allow you to view movie details, including genre, director, producers, cast ect. If a visitor of the app signs up for and account they can favorite movies or any media form the DB. 

Any user who uses IMDB might find this app fun to use. It’s much smaller in scale and more lightweight. 

In terms of data I will be using axios to fetch data from the OMDB API, a simple to use API with readable data. 

In terms of my schema on postgres I will likely have a users and favorites table so my data persists. These two tables will be connected for easier queries.

Since the API is simple to use I do not anticipate any major issues, there is a 1000 requests per day limit according to the documentation however I do not anticipate that will be a major issue. 

In terms of sensitive information I would say the user passwords, I plan  to protect their passwords using bcrypt. 

In terms of functionality this app lets you type in a movie/show ect. As soon as you start typing into the input the movie poster and titles will appear as a list on the page depending on what the user types in the text input. You can also click a movie/show/game from the list and view details such as director, producer, cast, release date ect. 

In terms of user flow you can type in whatever movie you want and you need not make a user account. You type in the movie/show/game, view the list click the movie /show/ game and can view the details. However if you wish to favorite an item you will have to create an account, if you already made one you must be logged in to view your favorites list or select new favorites. 

The app will be pretty simple it will feature some aspects of CRUD. My stretch goals are to perhaps filter by genre or director, that does not seem that difficult but it seems like sort of an extra feature, it would be nice to search by genre, or director however. If there are any other stretch goals I can think of I'll consider implementing those. 