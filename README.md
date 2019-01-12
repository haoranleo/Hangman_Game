<<<<<<< HEAD
Created: November 3, 2018
Last Modified: November 11, 2018


Description
-------------

This program is a server-client "Hangman" game for both single and two players. The maximum connection of client is set to be three (i.e. at most three games, both single and two player mode, are allowed). Every player are allowed only 6 times incorrect guess. 

Description
-------------

Team member: Haoran Li, Yingqiao Zheng
GT user name: hli656, yzheng394
GT ID number: 903377792, 903422795

Haoran Li is responsible for server.cpp and the original message format design and implementation;

Yingqiao Zheng is responsible for client.cpp, program test and modification to the newest requirement.


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

=======
# Hangman_Game
2
>>>>>>> ad1d715e296a2ebc1d76ba91fd7cd88559b3cdad
