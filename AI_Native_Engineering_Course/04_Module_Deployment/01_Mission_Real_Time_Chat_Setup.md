# Mission 1: Building the Chat App

## Objective

Build a real-time chat application using WebSockets.

## Key Concepts

- **WebSockets:** A persistent connection between browser and server (unlike HTTP's request-response).
- **Broadcasting:** Sending a message to all connected clients.
- **Socket.IO:** A library that makes WebSockets easy.

## The Task

Create a chat app where multiple users can send and receive messages in real time.

## Steps

1.  **Initialize Project:**
    - Create a new folder `realtime_chat`.
    - Initialize Git and create `.gitignore`.
2.  **Backend Setup:**
    - **Prompt:** "Create a Python/FastAPI backend using `python-socketio` for WebSockets. It should: 1. Handle client connections, 2. Broadcast received messages to all clients, 3. Track active users."
3.  **Frontend Setup:**
    - **Prompt:** "Create a simple `index.html` with: 1. A message input and send button, 2. A message display area, 3. Socket.IO client library to connect to the backend, 4. Display messages in real-time."
4.  **Test Locally:**
    - Open multiple browser tabs pointing to `localhost:8000`.
    - Send messages. They should appear in all tabs instantly.

## Vibe Check

- If messages don't appear, check the browser console for WebSocket connection errors.
- If only one tab works, you have a broadcasting issue.

## Success Criteria

Two browser tabs can send messages back and forth in real time.

