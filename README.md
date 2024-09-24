# Python Console Chat Application

This is a simple console-based chat application built with Python, following the client-server architecture. Multiple clients can connect to the server and exchange messages in real-time.

## Features
- **Client-Server Architecture**: The app allows multiple clients to join a chat room hosted by a central server.
- **Real-Time Messaging**: Messages sent by a client are broadcast to all connected clients.
- **Nickname Assignment**: Clients can choose their own nicknames.
- **Client Disconnection Handling**: The server handles client disconnections gracefully and notifies the remaining clients.

## Technologies Used
- **Python**: Core language for the application.
- **Socket Programming**: Used for client-server communication.
- **Threading**: Ensures multiple clients can communicate simultaneously.

## How It Works
1. **Server**: The server listens for incoming client connections and handles message broadcasting.
2. **Client**: Each client connects to the server, sends messages, and receives messages from other clients in real-time.

## Getting Started

### Prerequisites
- Python 3.x installed on your machine.

### Running the Server
1. Open a terminal and navigate to the directory containing `server.py`.
2. Run the following command:
    ```bash
    python server.py
    ```

### Running the Client
1. Open a new terminal for each client.
2. Navigate to the directory containing `client.py`.
3. Run the following command:
    ```bash
    python client.py
    ```
4. Choose a nickname and start chatting!
