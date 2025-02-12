<a href="https://www.linux.org/"><img src="https://img.shields.io/badge/Linux-CCAC00?style=for-the-badge&logo=Linux&logoColor=white" height="25em" alt="Linux"/></a>
<a href="[https://www.cprogramming.com"><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" height="25em" alt="C++"/></a>

# IRC

## Goal
Create a functional Internet Relay Chat (IRC) server and client that allows multiple users to connect, communicate in channels, and send private messages. \
**IRC** is a real-time messaging protocol used for group communication. 

## Key Features

1. Server:
- Handles multiple client connections simultaneously.
- Manages channels (creation, joining, leaving).
- Supports basic IRC commands like /join, /part, /msg, /nick, /kick, etc.
- Processes and broadcasts messages to the appropriate users and channels.

2. Client:
- Connects to the server.
- Sends and receives messages.
- Displays messages in a readable format.

3. Communication:
- Uses sockets for network communication (TCP/IP).
- Follows the IRC protocol.

## Skills Developed

- C++ Programming
- Socket Programming (for network communication).
- Multiplexing (select() or poll()) to handle multiple clients efficiently.
- Threading (optional, if required for advanced features).
