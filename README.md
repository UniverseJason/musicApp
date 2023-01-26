# musicApp introduction

This is a [MERN](https://www.mongodb.com/mern-stack) Music note full stack web application.

# Application dev-env requirement
1. Please make sure [Node](https://nodejs.org/en/) is installed
2. Please make sure a good text editor is installed (VS code is highly recommended)

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
1. open a **new** terminal and change to the dir
2. run `npm install` to get all packages installed
3. run `npm start` and you should see something like this:
```
Compiled successfully!

You can now view the client in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.1.72:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully
```

Finally, go to `http://localhost:3000` you should see the message that the server talks to the client

# Resource for study
- w3 school quick [overview](https://www.w3schools.com/nodejs/default.asp) for nodejs
