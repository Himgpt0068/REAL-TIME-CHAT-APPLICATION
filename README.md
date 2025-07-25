# Real-Time Chat Application

A fully functional real-time chat application that allows users to communicate instantly via WebSockets. Built with modern web technologies for seamless performance, user-friendly UI, and scalable real-time communication.


🧩 Features

🗣️ Real-time messaging (instant delivery)

👥 Multi-user chat rooms

🔐 User authentication (optional)

📱 Responsive UI (mobile-friendly)

📌 Message timestamps

🧹 Clear chat / auto-scroll

🌐 Deployed and accessible from anywhere



---

🛠️ Tech Stack

Frontend:

HTML5, CSS3, JavaScript

React.js or Vanilla JS (mention which one you used)

Socket.IO Client


Backend:

Node.js


Socket.IO Server

MongoDB / Redis (if user data or chat history is stored)



---

🗂️ Project Structure

real-time-chat-app/
  # Frontend files
├── client/              
│   ├── index.html
│   ├── style.css
│   └── script.js / App.jsx

# Backend server
├── server/                
│   ├── server.js
│   └── socket.js

   # Static files
├── public/             
├── package.json
└── README.md


---

📦 Installation & Setup

1. Clone the repository



git clone https://github.com/Himgpt0068/REAL-TIME-CHAT-APPLICATION/tree/main
cd real-time-chat-app

2. Install backend dependencies



cd server
npm install

3. Install frontend dependencies



cd ../client
npm install

4. Run both servers



# Backend (on port 5000)
cd server
node server.js

# Frontend (on port 3000)
cd ../client
npm start


---

🧪 Usage

1. Open the app in your browser.


2. Enter a username or join a room (if multi-room).


3. Start chatting in real-time with other users.


4. See messages appear instantly with no page reloads.




---

📸 Screenshots

Chat Window	Mobile View

	



---

📈 Future Enhancements

💾 Store chat history in a database

🔐 JWT-based authentication

🛑 User blocking / muting

📷 Image/file sharing

📱 PWA support for offline use



---


📄 License

This project is licensed under the MIT License.
