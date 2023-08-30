# ping-client-server

This assignment contains a PING server and PING client program that was written in Java. The server listens on a specified port and receives PING packets from clients. These packets include both headers and payloads, with the server capable of simulating packet loss based on a defined loss percentage. The server parses incoming packets to extract variables, such as IP addresses, ports, client IDs, and sequence numbers. It then prints information about received or dropped packets, capitalizes headers and payloads, constructs response packets, and sends them back to the clients. The server manages packet communication, loss simulation, and responses, for a PING server-client interaction.

How to compile and execute code:
Server
	- To compile use 'javac PINGServer.java' 
	- Finally to execute use 'java PINGServer <port number> <loss>'
Client
	- To compile use 'javac PINGClient.java' 
	- Finally to execute use 'java PINGClient <ip> <port number> <ClientID> <number of request packet> <wait time>'
