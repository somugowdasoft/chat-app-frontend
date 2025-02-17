---

# Chat App (MERN Stack)

A full-featured **Chat Application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js), allowing users to send and receive messages in real-time.

---

## Table of Contents
1. [Frontend](#frontend)
   - [Technologies](#technologies)
   - [Setup](#setup)
   - [Running the Frontend](#running-the-frontend)
2. [Backend](#backend)
   - [Technologies](#technologies-1)
   - [Setup](#setup-1)
   - [Running the Backend](#running-the-backend)
3. [Deployment](#deployment)

---

## Frontend

The **frontend** of the chat app is built using **React** and **Socket.IO** for real-time messaging.

### Technologies

- React.js
- Socket.IO (for real-time communication)
- Axios (for HTTP requests)
- Tailwindcss (for styling)
- React Router (for navigation)
- React-Hot-Toast

### Demo

`https://my-awesome-chat-app.netlify.app/login`

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/somugowdasoft/chat-app-frontend.git
   cd chat-app-frontend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your backend API URL:
   ```plaintext
   REACT_APP_API_URL=http://localhost:5000
   ```

### Running the Frontend

To start the development server, run:
```bash
npm start
```

This will run the frontend app at `http://localhost:3000`. You should be able to interact with the chat application and see real-time messages when the backend is running.

---
## Real-time Messaging

The **Socket.IO** integration handles the real-time communication between users.

### Socket Events

- **connection**: Triggers when a user connects to the chat room.
- **message**: Sends a new message to the room.
- **disconnect**: Triggers when a user disconnects from the chat room.

---


