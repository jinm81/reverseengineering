Sequelize homework reverse engineering code

##Password auth 

This app allows users to create a login and sign up page, and sign out securely.
All data is stored in a mysql database.

##Technology used
Bcryptjs -express mysql2 passport 

To use this app, please clone to the local storage, once this is complete please follow the steps

 Create a database called “passport_demo”
 Open config.json insert your password or process.env
Open terminal install dependency, run npm i
Run node server.js to connect to the server
Open default browser and insert http//localhost:8080 in the search bar


##Folders explained
Config and Middleware
Config.json (connection to the database)
Passport.js (contains javascript logic that runs user id and password to login.
Models
Index.js (connects to the database)
User.js (requires bcrypt for password encryption, 
Routes
Api-routes.js (shows all the routes for signing in, logging out and getting info for the specific user)
Html-routes.js (routes that checks if the user has already signed on if not shoots the user to the front page

Package.json (all the depencey to use the program and package info) 

Server.js (sets up Ports, creates express and middleware, sync databases and routes, logs err message if is connected successfully.)
