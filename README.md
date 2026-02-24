TCP & UDP Client-Server Communication System

### Description

This project is a Python-based client-server application that demonstrates communication over both TCP and UDP protocols.

The server provides multiple interactive services, and the client can choose different methods to execute various operations remotely.

The goal of this project is to demonstrate understanding of:

Socket programming
Network protocols (TCP vs UDP)
Client-server architecture
Data exchange and request handling

## Features

The client can request the following services from the server:
IPADDRESS – Displays the client's IP address
PORT – Displays the client's port number
COUNT – Counts characters or numbers based on input
ROLLTHEDICE – Simulates a dice roll
REVERSE – Reverses a given string
TIME – Returns the current server time
PALINDROME – Checks if a string is a palindrome
GAME – Simple interactive server-side game
GCF – Calculates the Greatest Common Factor of two numbers
CONVERT – Performs value/unit conversions
PRIME – Checks if a number is prime

## Technologies Used

Python 3
Python socket library
TCP protocol
UDP protocol

## Skills Demonstrated

Network socket programming
Handling multiple client requests
TCP vs UDP implementation differences
Server-side request parsing
Data validation
Basic algorithm implementation
Understanding of networking fundamentals

## Project Structure 
SERVERITCP.py
KLIENTITCP.py
SERVERIUDP.py
KLIENTIUDP.py

## How to Run
For TCP communication:
1️⃣ Start the Server
python SERVERITCP.py
2️⃣ Start the Client
python KLIENTITCP.py

For UDP communication:
1️⃣ Start the Server
python SERVERIUDP.py
2️⃣ Start the Client
python KLIENTIUDP.py

Make sure both client and server are configured to use the same IP address and port.

## Learning Objectives

This project was built to strengthen understanding of:

How network communication works
How applications exchange data
The difference between connection-oriented (TCP) and connectionless (UDP) protocols
Practical implementation of networking concepts

## Future Improvements

Add multi-client concurrency (threading or async handling)
Implement logging system
Add authentication mechanism
Improve error handling
Encrypt communication (TLS/SSL)
