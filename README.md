# Drag And Drop App
This is a simple app to upload files using drag and drop features of ReactJs

this project uses nodejs and expressjs for backend
for drag and drop feature it uses reacts fileuploader library
for databass it uses mongodb (for creating data use mongodb atlas)
to connect databass to nodejs it uses mongoose library

How to Start it--

1.  open the root folder in vs code which containes two folders 1.- client this has all front end . 2.-server this has all operations which includes apis and routes and databass connections
2.  open terminal go to client folder and type npm i to install all dependencies  and generate node_modules folder
3.  open another terminal for server folder and type npm i to install dependencies and generate node_modules folder (npm i)
4.  create a databass in mongodb atlas
5.  create a new cluster and generate your link to connect to our app
6.  paste the link in index.js file of server folder {
   mongoose.connect(
  "mongodb+srv://admin:admin@cluster0.xhxp5ho.mongodb.net/?retryWrites=true&w=majority",
  { useNewUrlParser: true, useUnifiedTopology: true }
  );
like this.

8.  start the server using npm start command then server will start
9.  After starting server Start front end in first terminal using npm start command this will start our app in browser
10.  now you can use the app

