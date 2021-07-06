Our goal is to build a web chat that holds a single chat room. 
Any user can connect to it from an open window/tab, 
 each connected user will see instantly any message sent, 
and new connected users will see the last 10 messages sent.

---------------------------------------------------------------------------------
The web app will be consist of 2 parts, the client and the server.
The client will contain 2 main components: 
a login form, where the user can write a use name to use for the chat throughout the conversation. 
The second component will consist of the chat messages, 
where each message that is sent, is viewed from anyone that’s connected to the chat room.
The server will accept two type of connections: 
 By creating an account, 
 The second connection the server manages is a WebSocket port to manage 
incoming connections and broadcast messages to all connected clients, in real time.
As we expect a large volume of data to be written to the database in a short amount of
 time and the data that we save are unstructured, it makes sense to use a NoSQL type of database. 
For this application, we will be using MongoDB.

------------------------------------------------------------------------------------

The ptoject is in Github under the name Chatbox-App
Github: https://github.com/Juventic/Mern_Stack
