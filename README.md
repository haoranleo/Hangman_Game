Description
-------------

This program is a server-client "Hangman" game for both single and multiple players. Players establishes connection with game-server through TCP socket. Players can find their partners online.

The game-server is designed to be able to manage maximum three 2-players games simultaneously by monitoring multiple socket descriptors.

Every player (if multiple player mode, then all players) are allowed only 6 times incorrect guesses per game. 

See project description here: [Project Description](./Project2_description.pdf)

Compile
------------

To compile server, simply run

		g++ server.cpp -std=c++0x -o server

To compile client, simply run

		g++ client.cpp -std=c++0x -o client


There is also a Makefile available, simply put it under the same path with server.cpp and client.cpp, both server and client would be compiled by running

		make

Execution
-----------

Run server using

		./server <portnumber>

Run client using 

		./client <server_IP_address> <portnumber>

