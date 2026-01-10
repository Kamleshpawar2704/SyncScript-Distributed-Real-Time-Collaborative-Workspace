# SyncScript – Distributed Real-Time Collaborative Workspace

SyncScript is a real-time collaborative web application that allows multiple users to join a shared workspace and collaborate simultaneously using live synchronization. The system is designed to demonstrate distributed systems, real-time communication, and full-stack cloud deployment.

---

## 🚀 Project Overview

SyncScript enables users to:
- Join a shared room
- Collaborate in real time
- See updates instantly across all connected clients
- Experience seamless synchronization using WebSockets

The project focuses on real-world challenges such as connection handling, synchronization, and scalable deployment.

---

## 🎯 Objectives

- Build a real-time collaborative platform
- Implement WebSocket-based communication
- Ensure low latency and synchronization accuracy
- Deploy a full-stack application on cloud platforms
- Understand distributed system behavior

---

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Socket io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)


## 🧑‍💻 Technologies Used

### Frontend
- React (Vite)
- TypeScript
- Axios
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO

### Deployment
- Frontend: Vercel
- Backend: Render

---

## ⭐ Unique Feature (Added Contribution)

### 🔔 Live Connection Status Indicator

A real-time connection status indicator was added to enhance reliability and user experience.

#### What it does:
- Displays **Connecting / Connected / Disconnected** status
- Automatically updates using Socket.IO lifecycle events
- Notifies users when the server connection fails or reconnects

#### Why it matters:
- Improves transparency in distributed systems
- Demonstrates fault tolerance handling
- Reflects real-world collaborative application behavior

---

## 🏗️ System Architecture

### High-Level Architecture
<img width="1101" height="358" alt="Screenshot 2026-01-10 193014" src="https://github.com/user-attachments/assets/f6e38fc9-4f79-49a8-a588-393f51ef1169" />


## 🔁 Real-Time Data Flow Explanation

1. User opens the application
2. Frontend loads UI from Vercel
3. Socket.IO establishes a persistent WebSocket connection
4. User joins a room
5. Any action (code edit, drawing, sync request):
   - Sent to backend
   - Broadcasted to all room members
6. All connected users receive updates instantly

---

## ⚡ Why Socket.IO?

- Real-time bidirectional communication
- Automatic reconnection handling
- Transport fallback support
- Ideal for collaborative applications

---

## 🌍 Deployment Architecture
<img width="1138" height="318" alt="Screenshot 2026-01-10 190923" src="https://github.com/user-attachments/assets/721288d4-cdda-4414-a419-f294c3bd125a" />



---

## 🧠 Project Explanation (For Viva)

### Introduction
This project is a real-time distributed collaborative workspace designed to simulate modern collaborative platforms. It focuses on real-time synchronization using WebSockets.

### Working
Each user joins a room. Any change made by one user is sent to the backend and broadcasted to all users in the same room, ensuring consistency and synchronization.

### Challenges Faced
- Socket.IO connection failures
- Environment variable misconfiguration
- CORS and polling issues
- Deployment integration between frontend and backend

### Solutions Implemented
- Correct backend URL handling
- Relative API paths for frontend
- WebSocket error handling
- Cloud deployment using environment variables

---

## 🧪 Learning Outcomes

- Understanding distributed systems
- WebSocket-based real-time communication
- Full-stack debugging
- Cloud deployment strategies
- System architecture design

---

## 📌 Future Enhancements

- Authentication
- Role-based access
- Persistent storage
- Chat history
- File sharing

---

## 📄 Conclusion

SyncScript demonstrates a practical implementation of real-time collaboration using modern web technologies. The project highlights challenges and solutions involved in building scalable distributed systems.

---

## 🔗 Live Deployment

- Frontend (Vercel): **[To be deployed]**
- Backend (Render): **[To be deployed]**


