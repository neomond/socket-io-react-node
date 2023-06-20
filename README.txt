----- for client
 yarn create react-app / yarn start 
 yarn add socket.io-client

----- for server
yarn init 
yarn add express cors nodemon socket.io

----- package.json
before dependencies add:
 "scripts": {
    "start": "nodemon index.js"
  },
