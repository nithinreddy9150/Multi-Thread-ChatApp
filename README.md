*COMPANY NAME:- CODTECH IT SOLUTIONS

NAME:- GUDDETI NITHIN REDDY

INTERN ID:- CT08QFW

DOMAIN:-JAVA PROGRAMMING

DURATION:-4 WEEKS

MENTOR:- NEELA SANTOSH*


# Multi-Thread-ChatApp

## Project Description
This project is a **Multithreaded Client-Server Chat Application** built using Java Sockets and multithreading. The application allows multiple clients to connect to a central server and exchange messages in real-time.

## Features
- Supports multiple clients simultaneously using multithreading.
- Real-time message broadcasting to all connected clients.
- Secure client-server communication using Java Sockets.
- Simple text-based chat interface.

## Technologies Used
- **Java** (Sockets, Multithreading, Networking)
- **JSON** (for Weather API in `Main.java`)
- **OpenWeatherMap API** (for fetching weather data)

## Prerequisites
- Java Development Kit (JDK) installed
- Internet connection (for weather API functionality)

## Installation and Setup
### 1. Clone the Repository

 git clone https://github.com/your-repo/multithreaded-chat-app.git
2. Compile the Java Files

 javac Server.java Client.java Main.java
3. Run the Server

 java Server
4. Run the Client(s)

 java Client
Open multiple terminals and run Client.java to test multiple connections.
File Structure

├── Client.java   # Client-side implementation
├── Server.java   # Server-side implementation
├── Main.java     # Fetches weather data using OpenWeatherMap API
└── README.md     # Project Documentation

How It Works:

The server starts and listens for client connections.
Each connected client runs on a separate thread.
Clients send messages to the server, which broadcasts them to all other clients.
The Main.java file can fetch weather data using the OpenWeatherMap API.

Example Usage:

Server is running...
Client 1: Hello
Client 2: Hi, how are you?
Server: Received: Hello
Server: Received: Hi, how are you?
Future Enhancements
Add user authentication.
Implement private messaging.
Enhance UI with a graphical interface.
License
This project is open-source and available under the MIT License.

Author
Developed by [G NITHIN REDDY] as part of an internship at CodTec
