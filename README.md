# Real-Time Chat App

A real-time group chat app built with React, Node.js, Express, Socket.IO and MongoDB.

## Features
- Join with a username
- Real-time messaging with Socket.IO
- Chat history saved in MongoDB
- Typing indicator
- Online users list
- Auto-scroll to latest message

## Tech Stack
- Frontend: React (Vite)
- Backend: Node.js, Express, Socket.IO
- Database: MongoDB Atlas (Mongoose)

## Setup

### 1. Backend
cd server
npm install
Copy .env.example to .env and add your MongoDB connection string
npm run dev
Server runs on http://localhost:5000

### 2. Frontend
cd client
npm install
npm run dev
App runs on http://localhost:5173

## Testing
Open the app in two browser tabs, join with different names and chat. Messages, typing and online status update live.

## Author
Shailender Gautam
