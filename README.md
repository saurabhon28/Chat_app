# Chat-Sat - Chat Application 
Chat-sat is chat application build with the power of MERN Stack. Users can chat with your contacts anywhere in the world.
![Alt text](screenshots/chat_dashboard.png)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.


Now create .env file for enviroment variable.

```shell
cd client
add  .env
cd ..
cd server
add  .env
cd ..
```

Now install the dependencies
```shell
cd server
npm install
cd ..
cd client
npm install
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd client
npm start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
npm start
```

Done! Now open localhost:3000 in your browser.

