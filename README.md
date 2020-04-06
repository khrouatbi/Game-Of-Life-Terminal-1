
To run on command prompt:
1. cd directory.
2. npm install
3. node app.js
4. go to localhost:3000

Works on Heroku.


## Server
- Node.JS
- Express
- socket.io

## files:

- `'/api/users/updateIsTyping'` :`socketId` and a `isTyping`.
- `'/api/messages/list'` : The messages
- `'/api/messages/submit'` : `socketId` parameter and a `body` parameter
- `'/api/messages/clear'` : `socketId`. Clears all messages.
- `'/api/grid/current'` : the current grid state
- `'/api/grid/start'` : Starts simulation
- `'/api/grid/pause'` : Pauses simulation
- `'/api/server/info'` : info about the server
- `'/api/users/list'` : connected users
- `'/api/users/rename'` :`socketId` and a `username`.

## Client
- Angular
- Angular's Boostrap UI
- socket.io
