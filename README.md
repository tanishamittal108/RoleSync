🚀 RoleSync Application (MERN Stack)

A full-stack RoleSync Web Application built using the MERN stack that allows users to explore job opportunities, apply for roles, and enables recruiters to post and manage job listings. The project focuses on real-world authentication, role-based access, and scalable frontend architecture.

🛠️ Tech Stack
Frontend

React.js (Vite)

Tailwind CSS

Redux Toolkit

Axios

shadcn/ui

React Router DOM

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

bcrypt

✨ Features
👤 User (Job Seeker)

User registration & login

Browse available job listings

Apply for jobs

View applied jobs

Secure authentication using JWT

🧑‍💼 Recruiter / Admin

Recruiter authentication

Post new job openings

Manage job listings

View applicants for a job

🔐 Authentication & Security

Role-based access control

Protected routes

Encrypted passwords

📁 Project Structure
RoleSync/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── server.js
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── hooks/
│       ├── lib/
│       ├── redux/
│       ├── utils/
│       ├── App.jsx
│       └── main.jsx
│
└── README.md



2️⃣ Backend Setup
cd backend
npm install
npm run dev


Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

📌 Key Learnings

Implemented JWT-based authentication

Designed RESTful APIs

Used Redux Toolkit for state management

Built scalable component-based UI

Integrated frontend & backend seamlessly

📈 Future Improvements

Resume upload feature

Job search & filters

Email notifications

Admin dashboard analytics

Deployment using Docker & AWS

👩‍💻 Author

Tanisha Mittal
3rd Year Student | MERN Stack Developer
