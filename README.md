# VisioTalk – Full-Stack Video Conferencing Web Application

A production-ready video conferencing web app developed using the MERN stack with WebRTC and Socket.io for real-time communication. Designed as part of a hands-on project using Apna College resources.

---

## 📌 Project Goal

To build a secure, reliable, and responsive video conferencing platform where users can join virtual meetings, interact in real-time, and experience seamless audio-video communication.

---

## 🚀 Key Features

- 🎥 One-to-one and group video conferencing (WebRTC)
- 💬 Real-time messaging using Socket.io
- 🔐 JWT-based user authentication
- 📱 Fully responsive UI using Tailwind CSS
- 🧭 Room creation and unique join links
- 🧠 Modular code with reusable React components

---

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS, Socket.io-client  
**Backend:** Node.js, Express.js, Socket.io  
**Database:** MongoDB  
**Authentication:** JSON Web Tokens (JWT)  
**Real-time Communication:** WebRTC, Socket.io

---

## 💡 How I Developed It

- Learned full-stack concepts via Apna College’s MERN tutorials
- Built custom signaling and peer-to-peer logic using WebRTC
- Implemented backend signaling server with Socket.io and Express
- Designed responsive UI with Tailwind and integrated video chat features
- Used JWT for secure login and room access

---

## ⚙️ How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/triveninelakurthi9/visiotalk.git
cd visiotalk
```

### 2. Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in both `/client` and `/server` folders.

#### Example `.env` for Server

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the Project

#### Backend

```bash
cd server
npm start
```

#### Frontend

```bash
cd ../client
npm start
```

### 5. Open in Browser

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📁 Folder Structure

```
visiotalk/
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── utils/
│       └── App.jsx
│
├── server/
│   ├── routes/
│   ├── socket/
│   ├── middleware/
│   └── server.js
│
├── .env
├── package.json
├── README.md
```
