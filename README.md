The project structure contains two folders, one for front-end and the other for back-end. All the data's from back-end are accessed through REST API call
 
/** Team Members: **/
 
1)AJAY GOVINDASAMY,20251024
2)AISHWARYA ARUN SUKALE,20251514
3)HRITIK GUPTA,20251132

We have hosted the project in Git HUB pages and below is the application demo for you reference.
 
Link: https://ajay-govindasamy.github.io/restaurant-onlinePUB/
 
The code folders are:
 
Front-end:
 
css folder - contains all the styling applied for the application
img - contains all the images included for the application 
js - contains all the script changes for dynamic interaction.
 
--> you can run index.html to start the application.
 
--> All the dynamic data's displayed are fetched from back-end REST API and diplayed using fetch() method in JavaScript

Back-end :

--> To run the project in your machine you need to have Node.js installed in your system.

--> Open your project directory and run the below command to install the required dependecies.

"npm install --save"

--> The project can be accessed at http://localhost:4000 .

See the documentation to access different routes.

The project folders are asa follows :
/models  -- Contains all the mongoose model classes
/routes   -- Contains all the endpoints to manage business, delivery and menuItems
index.js   -- Contains database settings and entry point of the server.
Procfile   -- This file is required by Heroku to run the application on Heroku Server.
.gitignore -- Contains list of all files and folder to be excluded when pushing code on BitBucket

Default Database Connection URL is "mongodb+srv://buuzuu:goforgold@cluster0.cisei.mongodb.net/cs615DB?retryWrites=true&w=majority".
It can be accessed from any where for now. To view all the collections download MongoDBCompass and paste the above link to connect.

You can also create your own cluster on MongoDB Atlas and replace the above url with your in index.js file. 
