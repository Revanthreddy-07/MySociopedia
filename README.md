--->The folders client and server both should be run simulatenously and the MongoDB database should be connected inorder to load the project.

--->The database is managed through MongoDB Atlas which connects to the project as an MONGO_URL in the .env file

---> create a .env file in the server folder. Write these lines where 'Your_Mongo_URL' is the URL of your own Mongo Database.
 
   MONGO_URL="Your_Mongo_URL"
   JWT_SECRET='somesuperhardstringtoguess';
   PORT=3001


1 Navigate through the server folder and find .env file and paste your unique MongoDB URL to get connected to database.
2 Go inside the client directory and use 'npm run start' command to start the client (Frontend).
3 Go inside the server directory and use 'node index.js' command to start the server (Backend).

THEN, THE PROJECT WILL BE LIVE ON YOUR LOCAL COMPUTER.
