# Messaging App

This is a simple messaging app where users can create an account, log in, and chat with others in real time. The app consists of both backend and frontend components.

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) installed
- A text editor like [VS Code](https://code.visualstudio.com/)

## How to Set Up the Project

### Step 1: Download the Code

1. Clone the repository by clicking on the following link:
   [MessagingApp GitHub](https://github.com/Rohit-Gupta31/MessagingApp/tree/main)
   
   You can clone it via Git by running this command in your terminal:
   ```bash
   git clone https://github.com/Rohit-Gupta31/MessagingApp.git
2. Open the folder in VS Code or your preferred text editor.

### Step 2: Setting Up the Backend
1. Open a terminal in VS Code and navigate to the backend directory:
   cd ./backend
2. Install npm to install all dependencies by running:
   npm install
   You also need to install the following packages:
   npm i bcryptjs cookie-parser cors dotenv express jsonwebtoken mongoose nodemon socket.io
3. Once everything is installed, start the backend server using:
   npm run dev
The backend server should now be connected to the database.

### Step 3: Setting Up the Backend
1. Open a terminal in VS Code and navigate to the frontend directory:
   cd ./frontend
2. Install npm to install all dependencies by running:
   npm install
   You also need to install the following packages:
   npm i axios react react-dom react-hot-toast react-icons react-redux react-router-dom react-scripts redux-persist socket.io-client web-vitals.
3. Once everything is installed, start the frontend server using:
   npm start


### Step 4: Using the Messaging App
1. After starting the frontend, the website will open with a Login page.

2. To create a new account, click on Sign Up and register a new account.

3. Open another browser (or run it on another system) and go to the same website using localhost:PORT where PORT is the port number displayed in your terminal after running npm start.

4. Create another account and start chatting with the new user.

Notes:
1. Make sure both the backend and frontend servers are running simultaneously.
2. You can chat between two accounts on different browsers or on different systems if both are connected to the same server.
