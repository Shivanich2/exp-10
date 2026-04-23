# 💬 Experiment-10: WebSocket Chat Application

---

## 📌 Overview
A full-stack real-time chat application using WebSocket for continuous communication between client and server.  
Built with **Spring Boot (backend)** and **React (frontend)**.

---

## 🎯 Objectives
- Enable real-time messaging without HTTP polling  
- Support multiple users with instant message broadcasting  
- Build a responsive UI using React  
- Integrate frontend and backend using STOMP protocol  

---

## 🛠️ Tech Stack

### 🔹 Backend
- Java  
- Spring Boot  
- WebSocket  
- STOMP  
- SockJS  
- Maven  

### 🔹 Frontend
- React  
- Vite  
- STOMP.js  
- SockJS  

---

## ✨ Features
- 💬 Real-time text messaging  
- 🖼️ Image sharing support  
- 🎤 Voice message support  
- ⚡ Live UI updates without refresh  
- 🔌 WebSocket endpoint (`/ws`)  
- 🔁 Message routing using `/app` and `/topic`  
- 🔒 Handles connection, disconnection, and errors  

---

## 📁 Project Structure

---

## ⚙️ Working
- Client connects to server via WebSocket  
- Messages are sent using STOMP protocol  
- Server processes and broadcasts messages  
- All connected users receive messages instantly  

---
**## Screenshots**
<img width="967" height="793" alt="Screenshot 2026-04-20 151200" src="https://github.com/user-attachments/assets/efc1fe6d-2a54-4bdc-bbb9-03285630d17d" />
<img width="787" height="911" alt="Screenshot 2026-04-20 225854" src="https://github.com/user-attachments/assets/e8ab85b8-885e-4927-a4fd-2cbbdd4f5d08" />
<img width="526" height="924" alt="Screenshot 2026-04-20 225913" src="https://github.com/user-attachments/assets/76964854-19bc-427c-831a-6ea4f5fa180c" />
<img width="1097" height="599" alt="Screenshot 2026-04-20 225955" src="https://github.com/user-attachments/assets/ac3d8192-5d3b-493d-a9e7-681b791bc613" />
<img width="1152" height="579" alt="Screenshot 2026-04-20 230017" src="https://github.com/user-attachments/assets/18596eb1-972c-48ae-a4d1-fa65666b83de" />
**
---

## 🚀 How to Run

### 🔹 Backend
```bash
cd backend
.\mvnw.cmd spring-boot:run

cd frontend
npm install
npm run dev

---



