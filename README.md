Mercansoft Chat App
Mercansoft is a real-time chat application built using Node.js, Express.js, Socket.io, and Redis. This repository contains the backend code for the chat application.

Table of Contents
Features
Prerequisites
Installation
Usage
Contributing
License
Features
Real-time communication: Chat with other users in real-time.
Socket.io integration: Utilizes Socket.io for real-time event-based communication.
Redis integration: Uses Redis as a data store for handling messages.
Scalability: The use of Redis allows for scalability and handling a large number of concurrent users.
Prerequisites
Before running the application, ensure you have the following prerequisites installed:

Node.js: Download and Install Node.js
Redis: Download and Install Redis
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/mercansoft-chat-app.git
Navigate to the project directory:

bash
Copy code
cd mercansoft-chat-app
Install the dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root directory and provide the following environment variables:

bash
Copy code
REDIS_HOST=<redis_host>
REDIS_PORT=<redis_port>
REDIS_PASS=<redis_password>
Replace <redis_host>, <redis_port>, and <redis_password> with your Redis server details.

Usage
Start the Redis server.

Start the Node.js server:

bash
Copy code
npm start
The server will start running at http://localhost:3000.

Open the frontend application to access the chat interface.

Start chatting with other users in real-time!

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Fork the repository.
Create a new branch: git checkout -b my-feature-branch.
Make your changes and commit them: git commit -am 'Add new feature'.
Push to the branch: git push origin my-feature-branch.
Submit a pull request.
License
This project is licensed under the MIT License.
