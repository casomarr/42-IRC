<a href="https://www.linux.org/"><img src="https://img.shields.io/badge/Linux-CCAC00?style=for-the-badge&logo=Linux&logoColor=white" height="25em" alt="Linux"/></a>
<a href="[https://www.cprogramming.com"><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" height="25em" alt="C++"/></a>

# IRC

## Goal
Create a functional Internet Relay Chat (IRC) server and client that allows multiple users to connect, communicate in channels, and send private messages. \
**IRC** is a real-time messaging protocol used for group communication. 

## Key Features to Implement

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
- Multiplexing (epoll()) to handle multiple clients efficiently.

## Technical Challenges

- Managing concurrency (handling multiple clients simultaneously).
- Implementing protocol adherence (follow IRC RFC specifications).
- Ensuring scalability and robustness (handling disconnections, malformed input, etc).

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository to your local machine:**
	```sh
	git clone git@github.com:casomarr/42-IRC.git
	```

2. **Navigate to the project directory:**
	```sh
	cd 42-IRC
	```

3. **Compile the project:**
	```sh
	cd IRC
   make
	```

4. **Run the server:**
	```sh
	./ircserv <port> <password>
	```
 Example : ```./ircserv 1200 testPassword```

## Usage

**Connect to the server:** open a new terminal and run
```sh
/connect localhost <port> <password>
```
Example : ```/connect localhost 1200 testPassword```


Example commands:
```sh
/join #channelName
```
To join a channel
```sh
/msg username message
```
To send a private message

See more commands in the "commands" folder.

## BONUS

**Run the BOT:**
	```sh
    cd Bonus
     make
	  ./ircbot <port> <password>
	```
 
**Join the bad_apple_bot channel:**
	```sh
    /join bad_apple_bot
	```
 

 



