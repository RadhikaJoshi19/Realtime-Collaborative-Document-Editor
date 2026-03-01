#REAL-TIME COLLABORATIVE DOCUMENT EDITOR

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RADHIKA JOSHI

*INTERN ID*: CTIS4971

*DOMAIN*: FULL STACK DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

Project Title
Real-Time Collaborative Document Editor

📖 Project Description

This project is a Real-Time Collaborative Document Editor that allows multiple users to edit the same document simultaneously over the internet.
The system enables live synchronization of content using WebSocket technology (Socket.IO) and ensures seamless communication between frontend and backend. Any change made by one user is instantly reflected to all connected users without refreshing the page.

The primary objective of this project is to demonstrate:
Real-time communication using WebSockets
Frontend–Backend integration
Asynchronous data synchronization
Database storage and retrieval
Dynamic and responsive UI development

🚀 Features

✔ Real-time collaborative editing
✔ Instant content synchronization
✔ Unique document ID system
✔ Auto-save functionality
✔ Multiple users support
✔ Backend database integration
✔ Responsive UI design

🛠 Technologies Used
🔹 Frontend:
React.js
HTML5
CSS3
JavaScript (ES6)
Quill Rich Text Editor

🔹 Backend:
Node.js
Express.js

🔹 Real-Time Communication:
Socket.IO (WebSocket)

🔹 Database:
MongoDB

🏗 System Architecture

Client A (Browser)
        ↓
   Socket.IO Connection
        ↓
   Node.js Server
        ↓
   MongoDB Database
        ↓
   Broadcast Updates
        ↓
Client B (Browser)

⚙️ How It Works

1.User opens the application.
2.A unique document ID is generated.
3.The client establishes a WebSocket connection with the server.
4.Server loads document from MongoDB (or creates a new one).
5.When a user types:
  Changes are sent to the server.
  Server broadcasts updates to all connected users.
6.Document is auto-saved at regular intervals.

📂 Project Structure
Real-Time-Collaborative-Editor/
│
├── server/
│   ├── server.js
│   ├── Document.js
│   └── package.json
│
└── client/
    ├── public/
    ├── src/
    │   ├── App.js
    │   └── Editor.js
    └── package.json

🧪 How to Run the Project
1️⃣ Start Backend
cd server
npm install
npm start
2️⃣ Start Frontend
cd client
npm install
npm start
3️⃣ Open Browser
http://localhost:3000
Open in multiple tabs to test collaboration.

🎯 Learning Outcomes

✔ Understanding WebSocket communication
✔ Real-time data synchronization
✔ Working with MongoDB database
✔ Implementing RESTful backend services
✔ Building scalable frontend using React
✔ Managing asynchronous events

📌 Deliverable

A live collaborative document editor with real-time synchronization, frontend–backend integration, and database storage.

📬 Future Improvements

Add user authentication
Cursor position tracking
Online users list
Version history
Conflict resolution using Operational Transformation (OT)
Cloud deployment

*OUTPUT*:

<img width="1873" height="976" alt="Image" src="https://github.com/user-attachments/assets/3051a81f-3925-46c8-b82f-1ebf9d5ca5e2" />
<img width="1909" height="1079" alt="Image" src="https://github.com/user-attachments/assets/a34e3d35-ad38-400b-8dd7-11012b9d45d4" />

<img width="1914" height="1079" alt="Image" src="https://github.com/user-attachments/assets/1f039a4d-c2ae-4730-bb84-2dbc3042ea2b" />
<img width="1912" height="1064" alt="Image" src="https://github.com/user-attachments/assets/bec0c8a1-c668-40f6-8710-c17529481d17" />
