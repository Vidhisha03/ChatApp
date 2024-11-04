
# Chatterbox - A Real-Time Chat Application

Chatterbox is a simple real-time chat application built with Node.js, Express, and Socket.IO. It allows users to join and exchange messages in real time, with messages visually differentiated as incoming or outgoing.

## Features

- Real-time messaging
- Clean and responsive UI
- Distinction between incoming and outgoing messages
- Simple, intuitive interface

## Project Structure

```
ChatApp/
│
├── public/
│   ├── style.css           # CSS styles
│   ├── client.js           # Client-side JavaScript with Socket.IO logic
│── index.html              # Main HTML file
├── server.js               # Express server setup and Socket.IO integration
├── README.md               # Project README
├── package.json            # Project dependencies and scripts
└── .gitignore              # Ignores node_modules and sensitive files
```

## Getting Started

Follow these instructions to set up and run Chatterbox on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) installed

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Vidhisha03/ChatApp
   cd ChatApp
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Install Nodemon (Optional)**

   Nodemon is a development dependency that automatically restarts the server when files change.

   ```bash
   npm install -D nodemon
   ```

4. **Install Socket.IO**

   ```bash
   npm install socket.io
   ```

### Usage

1. **Run the Server**

   Start the server using `node` or `nodemon`:

   ```bash
   node server.js
   ```

   Or, with automatic restarts on changes:

   ```bash
   npx nodemon server.js
   ```

2. **Open the App**

   Go to [http://localhost:3000](http://localhost:3000) in your browser to start chatting!

## Technologies Used

- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **Socket.IO** - Real-time, bidirectional communication
- **HTML/CSS** - Frontend structure and styling

