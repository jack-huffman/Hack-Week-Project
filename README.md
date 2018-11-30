# Hack-Week-Project
A group project made for our CS4830 class  

## Introduction and Background Information
Group Name: Error 404  
Group Members: Lee Offir, Austin Parrish, Jack Huffman, John Lund-Molfese  
## Problem:
Our users need an application to communicate quickly, in real time. 
## Solution
The solution is to create a real time chat application. 
## Implementation
We used Socket.io for client server communications, it uses websockets to send the data. WebSockets is a communication pipe that works both ways between client and server.
We also used a framework of Node.js, Express.js. Using npm we were able to install all we needed to get a functioning chatroom. This chat is designed to be either anonymous or with a username and refreshes once the user leaves the page to ensure some privacy.
## Future Work
* There are several items that we would like to add to the application. Currently, history is only stored in the browser's memory. We would prefer to keep all the information in a mongoDB database, which will horizontally be able to adapt to increasing load and more users. Also we wanted to add storage using a DB where the chats don't refresh and your able to view old chats and save them.   

 * Also, it would be good to have authentication. The best way to accomplish this would probably be through OAuth, so a user could use Google or Facebook to sign in. We would like to add a functional login that you would need to access the chat. Even though it is a public chat, having a login function would make it more secure for the users. This would allow the chat to be used for a specific organization or group of people, instead of allowing anyone on the internet to access it.

 
 * Finally, we want our users to be able to persistently log in and save profile pictures and names to a database. We could do that with MongoDB and get the pictures and names from OAuth. In order to provide more pre-filled information to the application, so users do not have to spend time entering their name, uploading a profile picture, and identifying themselves, we can implement OAuth.
The amount of information required would be fairly small, so users would not have to worry about privacy.
