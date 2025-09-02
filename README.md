# JobSprout – Full Stack Job Portal

JobSprout is a modern full-stack job portal built with React, Node.js, and MongoDB. It connects job seekers with employers and includes tools for career tracking, job management, and admin control.

## 🚀 Features

### For Job Seekers
- Secure JWT-based login & registration
- Search & filter jobs
- Apply and track applications
- Save/bookmark jobs
- Profile with resume, skills, and education
- User dashboard with analytics

### For Employers/Admin
- Admin dashboard with stats
- Post, update, and delete jobs
- Review and update application statuses
- Manage users

## 🛠 Tech Stack

**Frontend**: React, React Router, Axios, Recharts, FontAwesome  
**Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt  
**Others**: dotenv, CORS, custom CSS

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/dbe7dd7c-9fb0-408c-8c3c-3da963038684)
![image](https://github.com/user-attachments/assets/069ade25-8fa5-4a36-b1b4-9dac8324a2e9)




## 🧩 Project Structure

```

root/
├── client/       # React frontend
├── backend/      # Express backend
├── .gitignore
└── README.md

````

## ⚙️ Installation

```bash
git clone https://github.com/utk1college/JobSprout.git
cd JobSprout

# Install root deps if needed
npm install

# Backend setup
cd backend
npm install
cp .env.example .env

# Frontend setup
cd ../client
npm install
````




