# 🗣️ WebSocket Group Chat App

Welcome to the WebSocket Group Chat App! This is a simple yet powerful real-time chat application built using Node.js, Express, and WebSockets. 🖥️💬

🚀 Features
Real-Time Communication: Chat with multiple users in real-time using WebSockets.
Multiple Rooms: Join different chat rooms by simply navigating to a specific URL.
Persistent Connections: Maintain a persistent connection between clients and the server for a seamless chatting experience.
Simple Setup: Easy to set up and run on your local machine or network.
🛠️ Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusernamenotAnotherAverageJoe/websocket-groupchat.git
cd websocket-groupchat
Install Dependencies:
Make sure you have Node.js installed. Then, install the required packages:

bash
Copy code
npm install
Run the Application:
Start the server:

bash
Copy code
node server.js
or use nodemon for auto-restarting:

bash
Copy code
npx nodemon server.js
Access the Application:
Open your browser and go to:

bash
Copy code
http://localhost:3000/your-room-name
Replace your-room-name with any room name you like. Share this URL with others on the same network to chat together!

📂 Project Structure
server.js: Entry point of the application, starts the Express server.
app.js: Contains the main application logic and WebSocket handling.
static/: Directory for serving static files (CSS, JS, images).
chat.html: The main HTML file that acts as the client interface.
chatuser.js: Handles individual user connections and interactions.
Room.js: Manages chat rooms and broadcasting messages.
🧠 How It Works
Express serves static files and manages WebSocket connections.
WebSocket (express-ws) is used for real-time communication.
ChatUser class manages individual user connections, joining rooms, and handling messages.
Room class handles rooms, user management, and broadcasting messages.
📡 Network Access
If you want others on the same local network to join the chat:

Find your local IP address:
On Windows: ipconfig
On macOS/Linux: ifconfig or ip a
Replace localhost with your local IP address:
arduino
Copy code
http://192.168.x.x:3000/your-room-name
📸 Screenshots

(Add a screenshot here to show how the chat interface looks)

📝 License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as you like.

Happy Chatting! 💬🎉
This README provides a comprehensive overview of your WebSocket group chat application while adding a fun and engaging tone with emojis.
