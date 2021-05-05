# NCSC-LAB

1. Clone this repository.
2. To build the executable files, enter: ```make``` 
3. To run the server, enter: ```./chat_room_server 9669```
4. To run the client, enter: ```./chat_room_client <server_ip_port> 9669```
5. To use the commands while chatting, use:

>/q - disconnect from the chat room

>/uname  <new_username> - change your username

>/roomname  <new_roomname> - change the room name

>/shutdown - shutdown the chat server

>/w  <username> <message> - send a private whisper to the specified user

>/list - returns a list of current users

>/myname - returns your specified username
