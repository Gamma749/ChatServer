# ChatServer
A chat server implementation using Java threads, sockets

This project is a command line based chat server, which has a central chat server (ChatServer.java) which waits and accepts connections on a specified port. Clients (Client.java) may then connect to the Chat Server by specifing the IP address (or localhost if on the same machine) and the port number. Multiple connections can be formed (see code of ChatServer.java), and each is labeled with a client_ID. Clients use ReadWriteThread.java to send/recieve messages at any time.