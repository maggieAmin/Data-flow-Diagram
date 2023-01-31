# Data-flow-Diagram
What is responsible for defining the routes of the games resource?
create_router.js

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
There is two applications client and server they have different folders, the client responsible for display and interact with the users,  the server responsible for interface for the frontend to read and update the database

What are the the responsibilities of server.js?
Server.js is responsible for connecting the server to MongoDB driver, called db function, defined the collection, created router by call createRouter function

What are the responsibilities of the gamesRouter?
Create routers and apply changes on database
What process does the client (front-end) use to communicate with the server?
Restful API

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

Which of the games API routes does the front-end application consume (i.e. make requests to)?
It’s on GamesService.js using GET, POST AND DELETE

What are we using the MongoDB Driver for?
MongoDB Driver to connect MongoDB in JavaScript node.js server

![image](https://user-images.githubusercontent.com/105068818/215772850-85381598-fd03-4451-afce-018b6a75dd48.png)
