# Habit Tracker

A full-stack **Habit Tracking** web application built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It enables users to create and manage daily habits, monitor completion streaks, and visualize their progress through an interactive dashboard.

## Features

* Secure user authentication using JWT
* User registration and login
* Create, update, and delete habits
* Track daily habit completion
* Prevent duplicate daily entries
* Dashboard with streaks and completion statistics
* Progress visualization using charts
* Responsive and user-friendly interface

## Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* Recharts

### Backend

* Node.js
* Express.js
* JWT Authentication
* bcrypt

### Database

* MongoDB Atlas
* Mongoose

---

## Project Structure

```
habit-tracker/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/FahadHassan07/habit-tracker.git
cd habit-tracker
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=3030
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start the backend:

```bash
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Authentication

* Passwords are securely hashed using bcrypt.
* JWT is used for authentication and authorization.
* Protected routes restrict access to authenticated users.

## Future Improvements

* Email verification
* Habit reminders and notifications
* Calendar view
* Dark mode
* Social login
