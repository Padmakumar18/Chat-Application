# Chat Application

A real-time chat application built using **Spring Boot, WebSockets (STOMP), React, and SockJS**. This project enables users to send and receive messages in real time using a publish-subscribe model.

## 🚀 Features

- Real-time messaging with WebSockets
- User-friendly chat UI
- Backend built with Spring Boot
- Frontend developed using React
- STOMP protocol for message transmission
- SockJS fallback for browser compatibility

## 🛠️ Tech Stack

### **Frontend:**
- React
- SockJS Client
- STOMP.js
- Bootstrap (for styling)

### **Backend:**
- Spring Boot
- WebSockets
- STOMP protocol
- Spring MVC

## 📂 Project Structure

```
chat-application/
│── backend/
│   ├── src/main/java/com/example/chat/
│   │   ├── config/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── service/
│   │   ├── ChatApplication.java
│   │   ├── WebSocketConfig.java
│   ├── pom.xml (Maven dependencies)
│
│── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
│   ├── public/
```

## 🎯 Setup & Installation

### 1️⃣ Backend (Spring Boot)
1. Navigate to the `backend/` folder:
   ```sh
   cd backend
   ```
2. Build and run the project using Maven:
   ```sh
   mvn spring-boot:run
   ```
3. The backend will start at `http://localhost:8080`

### 2️⃣ Frontend (React)
1. Navigate to the `frontend/` folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```
4. Open `http://localhost:3000` in your browser.

## ⚙️ WebSocket Endpoints
| Endpoint             | Description           |
|----------------------|----------------------|
| `/topic/messages`   | Subscribes to messages |
| `/app/sendmessage`  | Sends a message       |

## 📝 To-Do List
- [ ] Add user authentication
- [ ] Implement chat rooms
- [ ] Store chat history in a database

## 🙌 Contribution
Feel free to submit issues or pull requests to improve this project!

## 📜 License
This project is open-source and available under the MIT License.
