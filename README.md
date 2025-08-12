# 🗨️ Text-Based Chat App (Python Socket Programming)
### 📌 Description 
This is a simple terminal-based chat application built using Python’s socket and threading modules. The program allows two users to communicate with each other through a server using TCP sockets on localhost.
Perfect for learning how networking, threading, and real-time message exchange work in Python!
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🧠 Features
Two-way real-time communication over sockets

Multi-threaded server for handling multiple clients

Message broadcasting to connected clients

Lightweight and easy to run locally

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### ⚙️ Technologies Used
Python 3.x

Socket Programming

Threading

Terminal/Console I/O

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🚀 How It Works
#### Server
Listens on a specific HOST and PORT

Accepts up to 2 client connections

Forwards messages received from one client to the other

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#### Clients
Connect to the server

Send and receive messages concurrently using threads

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📦 Project Structure
# Server code
start_server()

# Client code (User1, User2)

start_client("User1", ["Hi", "How are you?"])

start_client("User2", ["Hello", "I'm good, thanks!"])

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📝 Sample Output 

[Server] Started and waiting for clients...

[Server] Client connected from ('127.0.0.1', 50592)

[Server] Client connected from ('127.0.0.1', 50594)

[User1] Connected to server.

[User2] Connected to server.

[User1 got]: User2: Hello

[User2 got]: User1: Hi

[User1 got]: User2: I'm good, thanks!

[User2 got]: User1: How are you?

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📌 Notes
This is a local-only chat app using 127.0.0.1 (loopback).

Only supports two clients, but you can scale it up with logic changes.

Handling socket connections and exceptions

