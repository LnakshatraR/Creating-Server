# Local Server Setup Examples

This repository contains example code for setting up local servers. These examples demonstrate how to serve static files, execute PHP files on demand, and create a Node.js server that displays a simple message.

## Repository Contents

- **index.html** - A simple HTML file served by a local static server.
- **index.php** - A PHP file executed on demand using XAMPP.
- **my-server.js** - A Node.js script that creates a server and sends a "Hello World from Nakshatra Reddy!" message to the browser.

## Getting Started

Follow these instructions to get the local servers running on your machine.

### Prerequisites

Before you start, make sure you have the following installed:

* [Node.js](https://nodejs.org/en/) and npm (Node Package Manager)
* [XAMPP](https://www.apachefriends.org/index.html) (or an alternative like WAMP or MAMP for PHP support)
* A text editor or IDE (e.g., [Visual Studio Code](https://code.visualstudio.com/))

### Setup and Running

#### Static HTML Server

1. Navigate to the directory containing *index.html*.
2. If you are using Node.js, install the *localhost* package globally:  <br>
$ npm install -g localhost
3. Start the server:  <br>
$ localhost
4. Open your browser and go to [http://localhost:8080](http://localhost:8080) to view the HTML page.

#### PHP File Execution

1. Move *index.php* to the *htdocs* folder of your XAMPP installation.
2. Start the XAMPP Apache server.
3. Open your web browser and navigate to:
    [http://localhost/index.php](http://localhost/index.php)

#### Node.js Server

1. Ensure Node.js is installed.
2. In the terminal, navigate to the folder containing *my-server.js*.
3. Run the Node.js server: <br>
$ node my-server.js
4. Open your browser and access the server at [http://localhost:3000](http://localhost:3000) to see the message.