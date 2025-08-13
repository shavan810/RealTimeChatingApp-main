# 💬 Real-Time Chatting Application

A real-time web-based chatting application built using **Node.js**, **Express**, **Socket.IO**, and **MongoDB**. 
This project enables users to send and receive messages instantly, simulating live communication similar to modern messaging platforms.

---

## 🚀 Features

- 🔄 Real-time messaging using **WebSockets (Socket.IO)**
- 🧑‍🤝‍🧑 Supports multiple users
- 💬 Instant chat updates without page refresh
- 🗃️ Message persistence using **MongoDB**
- 🔒 [Optional] JWT-based user authentication (if added)
- 📱 Responsive UI with message input and chat display

---

## 🛠️ Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | Node.js, Express.js |
| Real-time    | Socket.IO          |
| Database     | MongoDB            |
| Others       | WebSockets, REST APIs |

---

## 📁 Project Structure

RealTimeChattingApp/
│
├── server/
│ ├── server.js # Main server logic
│ ├── socketHandler.js # Socket.IO connection and event handling
│ ├── models/ # MongoDB schema
│ └── routes/ # API routes (if any)
│
├── client/
│ ├── index.html # Frontend UI
│ ├── style.css # Chat styling
│ └── script.js # Frontend logic for socket communication
│
├── package.json
└── README.md


---

## ⚙️ How to Run Locally

### Prerequisites:
- Node.js and npm
- MongoDB running locally or cloud (MongoDB Atlas)

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RealTimeChattingApp.git
   cd RealTimeChattingApp

