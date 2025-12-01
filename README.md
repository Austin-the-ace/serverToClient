# serverToClient
ReadMe for current code

Function parameters/output details to be added to aid in drafting report
## Files
chatserver.c

chatclient.c
## Description
This a multi-threaded chatroom used in Linux for commmunication between a server and a client.
### Environment
Written in C for Linux Command Line
### Procedure
- Chat server uses socket API to listen on join port for join requests from chat clients
- Join requests consist of client usernames and room names
- Maximum number of clients per room is 10
- Server processes join requests by searching for chat rooms
- Uses multi-threading to create worker threads for each new room
- Server connects clients to desired chat room
- Connected clients receive and send messages to all other occupants through socket
- Maximum number of rooms is 20
- Maximum number of clients per room is 10
- Clients can leave via "/leave" and confirming the request
- UDP broadcasts are sent in the discoverServer function.
## Contributors
Melissa Swindall

Austin Stuart

*November 30, 2025*
*COSC 4333*
