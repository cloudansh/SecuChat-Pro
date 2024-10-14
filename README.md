# Private-Chat-Application-using-MongoDB-and-Socket.io
This repository hosts a fully operational private chat application built with MongoDB, Socket.io, and Express. It enables real-time chatting and allows users to retrieve previous chat history when logging in later.

## Tech Stack:
- **HTML, CSS** (for the front-end interface)
- **JavaScript** (handling both front-end behavior and back-end functionality)
- **Node.js & Express.js** (back-end server setup)
- **Socket.io** (enables real-time communication between client and server)
- **MongoDB** (used for storing chats, online users, etc.)

## App Features:

- Real-time private chat between two users
- Chat history is retrievable when users log in again
- Private chats are not visible to other online users
- Messages sent to offline users can be retrieved when they log in

## Usage Instructions:

1. Ensure [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) are installed. Verify by running:

  ```cmd
    $ node -v
    $ mongod --version
  ```

2. Clone the repository and set up the application:
   ```cmd
    $ git clone https://github.com/cloudansh/SecuChat-Pro/
    $ cd SecuChat-Pro.io
    $ npm install
    $ node server.js
   ```
3. With the server running, visit http://localhost:5000/chat.html to access the chat interface.


4. Enter your name and the name of the second person, then press done to connect. The chat history between the two will be displayed.


5. Open the same URL in another browser/tab to complete the connection.


6. Send messages from either end to test functionality.


7. Exit by closing the browser when done.

