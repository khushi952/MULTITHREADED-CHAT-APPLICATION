# MULTITHREADED-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: KHUSHI SAHU

INTERN ID:CT4MTGYC

DOMAIN: JAVA PROGRAMMING

DURATION: 16 WEEKS

MENTOR: NEELA SANTOSH

 # DESCRIPTION

This task  is a Multithreaded Chat Application built using socket programming and threading in Java . It enables real-time communication between multiple clients and a server, allowing users to exchange messages efficiently and simultaneously.It’s a foundational networking project ideal for learning the core principles of concurrent programming, client-server architecture, and real-time communication over a network.

# 🔧 Key Features
 * Multithreaded Server: Efficient handling of multiple clients concurrently.

 * Real-Time Messaging: Ensures instant delivery of messages to all users connected.

 * Simple Command-Line Interface (CLI): Lightweight and fast interaction using the terminal.

* Broadcast System: Every message sent by a client is broadcast to all other clients via the server.

 * Scalable: The application structure allows easy enhancements like user authentication, private messages, or even a GUI frontend.

# 🛠️ Task Overview
The chat system is built around a client-server model:
The server acts as the central communication hub. It continuously listens for incoming connections from multiple clients and maintains active sessions with all connected clients.
Each client connects to the server and can send or receive messages. Messages sent by any one client are broadcast to all others via the server.

The main highlight of this project is the use of multithreading on the server side. For every new client connection, a separate thread is spawned to handle communication with that specific client. This ensures that the server can manage multiple users at once, without blocking or waiting on a single connection.


# 💡 How It Works
 * Server Startup: The server opens a socket, binds to a specific IP and port, and starts listening for client connections.

 * Client Connection: A client connects to the server using the server’s IP and port. On connection, the server spawns a new thread to manage that client’s session.

 * Message Handling: When a client sends a message, the server receives it and relays it to all other connected clients.

 * Thread Safety: Each client is handled in its own thread, preventing message delays or crashes due to multiple connections.


# 🚀 Future Improvements
GUI-based client

User authentication

Private rooms

Emoji & media support

# Output
Server
![Image](https://github.com/user-attachments/assets/f24d3e76-28ea-462f-900f-f51963a3775e)
