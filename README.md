# madLibz

This Mad Libz app is a fun game where users enter in various words to complete a story in a hilarious and unexpected way. With the added frontend and backend components, this app is more versatile and robust, catering to the needs of more advanced users.

## Features

- User can replace words in a single madlib given, with provided input field for verb, noun, adjective
- Users saved generated madlib
- Users can create new madlib and store into database
- Backend component that allows for backend interaction, functionality, and security

## Usage
Navigate to the project directory in your terminal, run npm i, run MySql and enter USE madlibz_db;, run node seeds/index.js to run seed file, run npm start to start application. User will be prompted with a random mad libz sentence in the database and chose what noun, adjective, and verb that will populate into the story/sentence. The completed story will be displayed. Use /madlibz in url to get to madlibz then go to saved madlibz to reveal story/sentence created. 

## Technologies Used

Node.js, Express.js, Handlebars, Sequelize, External CSS Tailwinds, mysql2, bcrypt, dotenv.


### Links
Repository: https://github.com/Coding-bootcamp-project-2/madLibz
Heorku Deployed: https://madlibz-game-771d3cfc4525.herokuapp.com/

### Screenshots

[screenshots](./img/homepage.png)
[screenshots](./img/loggedin.png)
[screenshots](./img/savedmadlibz.png)
[screenshots](./img/userinput.png)
[screenshots](./img/signuppage.png)



