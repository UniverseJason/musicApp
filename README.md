# musicApp introduction
This is a [MERN](https://www.mongodb.com/mern-stack) Music note full stack web application.

# Application dev-env requirement
1. Please make sure [Node](https://nodejs.org/en/) is installed
2. Please make sure a good text editor is installed ([VS code](https://code.visualstudio.com/) is highly recommended)

# How to run?
We got 2 folders:
- **api** for nodejs server side logic
- **client** for react client-side logic

First, we need to run the server:
1. In the terminal, change dir to api
2. run `npm install` to get all packages installed
3. run `npm start` and you should see something like this:
```
npm start

> musicapp@0.0.0 start
> nodemon ./bin/www

[nodemon] 2.0.20
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node ./bin/www`
```
Second, we need to run the client:
1. open a ***new*** terminal and change dir to client
2. run `npm install` to get all packages installed
3. run `npm run dev` and you should see something like this:
```
  VITE v4.1.4  ready in 215 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

Finally, go to your **local host** you should see the client side running!

# Resource for study
- w3 school quick [overview](https://www.w3schools.com/nodejs/default.asp) for nodejs
- [mozilla web doc](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs) have comprehensive tutorials for server and client programming!
