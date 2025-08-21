# ChatterBox

## Project Overview

A comprehensive WhatsApp clone built with the MERN stack featuring real-time messaging, group chats, and multimedia sharing. The application implements Socket.IO for instant communication, JWT-based authentication with OTP email verification, and MongoDB for persistent message storage. Advanced features include status updates with comments, image sharing capabilities, and offline message synchronization ensuring seamless user experience across sessions.

This full-stack implementation demonstrates modern real-time web application development with secure authentication, database design, and WebSocket communication protocols.

## Project Structure

```
Directory structure:
└── chiragbansal511-chatterbox/
    ├── backend/
    │   ├── index.js
    │   └── package.json
    └── frontend/
        ├── README.md
        ├── package.json
        ├── public/
        │   ├── index.html
        │   ├── manifest.json
        │   └── robots.txt
        └── src/
            ├── App.css
            ├── App.js
            ├── App.test.js
            ├── index.css
            ├── index.js
            ├── reportWebVitals.js
            ├── setupTests.js
            ├── socket.js
            ├── components/
            │   ├── addgroup.js
            │   ├── privateroute.js
            │   └── status.js
            └── pages/
                ├── home.js
                ├── index.css
                ├── login.js
                ├── sendmessage.js
                ├── signup.js
                └── verifyotp.js
```

## Technical Details

**Technology Stack:**
- **Frontend**: React 18, Socket.IO Client, Material-UI
- **Backend**: Node.js, Express.js, Socket.IO Server
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT tokens with OTP email verification

**Core Features:**
- Real-time messaging with Socket.IO WebSocket connections
- Individual and group chat functionality
- JWT authentication with email OTP verification via Nodemailer
- Image upload and sharing with file storage
- Status updates with comment system
- Offline message storage and synchronization
- Message delivery status tracking

## Data Flow Model

<img width="367" height="790" alt="image" src="https://github.com/user-attachments/assets/f60d902d-3a2a-4ba6-90e9-8183050c3643" />


## User Interface

  Login /Signup
  <img width="1918" height="862" alt="Screenshot 2025-08-21 140220" src="https://github.com/user-attachments/assets/6a5bd113-110d-43cd-8506-6f04530e079f" />

  Chat
  <img width="1900" height="865" alt="Screenshot 2025-08-21 135229" src="https://github.com/user-attachments/assets/a837e99f-938f-4275-ac1b-0d290bfc1ae5" />

  Status
  <img width="1917" height="872" alt="Screenshot 2025-08-21 140143" src="https://github.com/user-attachments/assets/3630ddd5-63f1-4be6-9b20-f13d6e6fb6f8" />
  

## How to Use and Play

### Installation
```bash
git clone https://github.com/chiragbansal511/ChatterBox.git
cd ChatterBox
# Install server dependencies
cd backend && npm install
# Install client dependencies
cd ../frontend && npm install
# Configure environment variables (MongoDB, JWT, Email)
# Start server
cd ../backend && npm start
# Start client
cd ../frontend && npm start
```
Server: `http://localhost:80` | Client: `http://localhost:3000`

### Usage Flow
1. Register with email and verify via OTP code
2. Login to access main chat interface
3. Start individual chats or create group conversations
4. Send text messages, images, and share status updates
5. Receive real-time messages and offline message sync

### Controls & Features
- **Controls**: Message input, emoji picker, file upload, contact search, group management
- **Features**: Real-time messaging, group chats, image sharing, status updates, offline sync, message delivery status
