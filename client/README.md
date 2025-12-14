# PrimeTrade Frontend Developer Task

A modern, scalable Task Management Dashboard built with the MERN Stack (MongoDB, Express, React, Node.js). This project demonstrates secure authentication, CRUD operations, and responsive UI/UX.

## 🚀 Features
* **Authentication:** Secure Login/Register with JWT & Bcrypt password hashing.
* **Dashboard:** Interactive task management with real-time updates.
* **Filtering:** Filter tasks by status (Pending/Completed) and search by title.
* **Security:** Protected routes ensuring only authenticated users can access data.
* **UI/UX:** Responsive design using Tailwind CSS with glassmorphism effects.

## 🛠️ Tech Stack
* **Frontend:** React (Vite), Tailwind CSS, Axios, React Router
* **Backend:** Node.js, Express.js
* **Database:** MongoDB Atlas
* **Tools:** JWT-Decode, Cors, Dotenv

## ⚙️ Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone https://github.com/vikram-p23/primetrade-assignment.git
    cd primetrade-assignment
    ```

2.  **Setup Backend**
    ```bash
    cd server
    npm install
    # Update MONGO_URI in server.js with your connection string
    npm start
    ```

3.  **Setup Frontend**
    ```bash
    cd client
    npm install
    npm run dev
    ```

4.  **Access the App**
    Open `http://localhost:5173` in your browser.
