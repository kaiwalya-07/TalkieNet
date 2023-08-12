# TalkieNet
A real-time chat room application utilizing socket programming and TCP/IP protocols. Clients connect to a central server over TCP/IP, enabling seamless communication and message exchange within the chat room environment.

## Features

- Multiple clients can join a chat room.
- Clients can send and receive messages in real-time.
- Admins can approve join requests from new members.
- Admins can perform actions like transferring adminship and kicking members.
- Communication is facilitated through TCP/IP sockets.

## How to Run

###  ON Linux or Windows 

1. Open a terminal.

2. Navigate to the project directory:
   ```
   cd path/to/project
### Run the server using
    ``` 
    python3 server.py localhost 8000
### Open another terminal window and run multiple client instances:
       ```
       python3 client.py localhost 8000
       

### Usage
Follow the on-screen instructions in the client terminal for creating/joining groups and sending/receiving messages.
Admins can use specific commands to manage the chat room.
Press Ctrl+C in the terminal to stop the server and client instances.


### Dependencies
Python 3.x

### Notes
This is a simplified demonstration and may require further refinement for production use.
Proper error handling, security considerations, and scalability are important aspects for real-world applications.
Replace `path/to/project` with the actual path to your project directory.
