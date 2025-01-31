# Real-Time Chat Application

## Overview
This is a **real-time chat application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) with **Socket.IO** for seamless bidirectional communication. It enables users to chat in real time with an intuitive and responsive interface.

## Features
- **Real-time messaging** using **Socket.IO**
- **User authentication** (signup, login, logout)
- **Private and group chat support**
- **Message persistence** (MongoDB to store chat history)
- **Responsive UI** built with **React & Chakra UI**
- **Context API for state management**
- **Secure authentication** using JWT tokens
- **Typing indicators and message notifications**
- **Optimized backend API with Express.js**

## Tech Stack
### **Frontend**
- React.js
- Context API (for state management)
- Chakra UI (for UI components)
- Axios (for API requests)

### **Backend**
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- Socket.IO

### **Other Tools**
- dotenv (for environment variables)
- bcryptjs (for password hashing)
- CORS (for cross-origin requests)

## Installation & Setup
### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/chat-app.git
cd chat-app
```
### 2. Install dependencies:
#### **Backend**
```bash
cd backend
npm install
```
#### **Frontend**
```bash
cd frontend
npm install
```
### 3. Set up environment variables:
Create a `.env` file in the backend directory and add:
```env
PORT=******
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=**********
```

### 4. Run the application:
#### **Backend**
```bash
cd backend
npm start
```
#### **Frontend**
```bash
cd frontend
npm start
```

## Usage
1. Sign up or log in to your account.
2. Start a private or group chat.
3. Send and receive real-time messages.
4. Messages persist in the database.
5. Log out securely when done.

## Future Enhancements
- **File & Image sharing**
- **Video & Voice calling integration**
- **Push notifications**
- **End-to-end encryption**

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! Feel free to fork the repository and create a pull request.

---
Made with ❤️ by [Your Name]

