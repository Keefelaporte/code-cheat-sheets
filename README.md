Module 8 Cheat sheet,
Create repo for project,
Clone project,
Npm init -y (no need to git init),
npm install --save express --save dev nodemon(if it doen't work try --save-dev nodemon) --save mysql --save sequelize-cli --save dotenv, and dev:nodemon in the scripts of package.json
Create index.js,
Create git.ignore for modules,
Create your index.js with const (express = require('express'),('./models'),('body-parser'), app = express()
Create a config folder with .env init and a sequelize.js
Create a Models folder for two .js files(another index.js, and a subscriber.js)
In the Index.js
In the subscribers.js
In the index.js create a app.post subscribe you add res.status and .send with message to test in postman.(comment out other post)
Create app.listen(1337, () => { console.log("Started")})
Create app.post for subscribe, unsubscribe, feedback, contact email
Open/Download Postman and test the connection
Run nodemon in terminal to test 
Go in the terminal and git status, add ., commit "with message here",push (now project in the hub)
