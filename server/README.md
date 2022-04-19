# Getting Started with the MERN Blog

This project is intended to allow a user to quickly begin programming a free-standing SPA using React, Express, Node, and MongoDB.

## Available Scripts

If you desire to initialize using the React frontend, all you have to do is navigate to the directory /client and run a couple commands to get your frontend running.

Then, you'll simply do the same with the node backend. Viola!

### For Node/Express.JS

This initializes a lightweight mock server which runs Express.JS / Node.JS to allow simple database queries to a MongoDB cloud database.

#### Installation

If you do not have Node or npm, please go [download it here](https://nodejs.org/en/download/) and make sure to install all options including NPM & environmental paths.

Next, clone this project to your machine. Open the backend/node folder in your terminal and run the Node command 'npm install'. This will install all the necessary NPM packages for your server to function.

```bash
npm install
```

Once the packages are done installing, run 'npm start'. 

```bash
npm start
```
Your server will start, and you should see a notification in your terminal of success. The Express server will run on port 8081 of your localhost. If you visit [http://localhost:8081/](http://localhost:8081/), you should now see 'Hello World'. This will tell you that the server is running.

The Express server continually runs via the nodemon library. If you would like to end the program, close your terminal or run 'killall -9 node' from elsewhere.

```bash
killall -9 node
```

### Usage

This Express server allows a user to request account information from a MongoDB cloud database. It is meant to be run in tandem with the frontend SPA in React.

When using the server to access the accounts for the demo UI, please initialize the server first (or the UI will not have any data to load).
