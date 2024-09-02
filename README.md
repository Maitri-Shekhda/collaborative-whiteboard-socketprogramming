# Collaborative Whiteboard Using Socket Programming

A real-time collaborative whiteboard application that allows multiple users to draw on a shared canvas simultaneously. The project leverages Python's socket programming to enable real-time communication between clients and a server, facilitating collaborative drawing over a network.

## Overview

The Collaborative Whiteboard is a multi-user application that enables real-time collaboration on a shared drawing canvas. It uses a client-server architecture, where a server manages client connections and synchronizes drawing data across all connected clients. This project is an excellent demonstration of socket programming, multithreading, and real-time network communication in Python.

## Features

-**Real-Time Drawing**: Multiple users can draw on the whiteboard at the same time, and their drawings are updated in real-time for all users.
-**Client-Server Architecture**: Centralized server handles all client connections and broadcasts drawing updates.
-**Graphical User Interface (GUI)**: User-friendly interface built with Tkinter for easy drawing and collaboration.
-**Multithreaded Server and Client**: The server and client use multithreading to handle multiple connections and GUI updates simultaneously.

## Technologies Used

-**Python**: The programming language used to build the application.
-**Socket Programming**: Used for network communication between the server and clients.
-**Tkinter**: Python's standard GUI library used to create the drawing interface.

## Architecture

The project follows a client-server architecture where:

-The Server acts as a central hub that manages all client connections and handles the broadcasting of messages to ensure real-time synchronization.

-The Clients connect to the server, send drawing actions, and receive drawing updates from other clients via the server.

## Setup and Installation

1.**Clone the Repository:** 
git clone https://github.com/Maitri-Shekhda/collaborative-whiteboard-socketprogramming.git
cd collaborative-whiteboard-socketprogramming

2.**Install Required Libraries:**
pip install tkinter

3.**Run the Server:** 
python server.py

4.**Run the Client(s):** 
python client.py

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is open-source and available under the MIT License.
