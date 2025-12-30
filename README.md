# PurpleMerit – User Management System (Frontend)

This project is the frontend implementation of a User Management System developed as part of the PurpleMerit Backend Developer Intern Assessment.

The application allows users to sign up, log in securely, and access a protected dashboard.

---

## Live Application

Frontend (Vercel):  
https://purplemerit-frontend-le3t1xs5d-priyanshi-bajpais-projects.vercel.app/

Backend (Render):  
https://purplemerit-user-management-wdha.onrender.com

---

## Tech Stack

Frontend:
- React.js
- React Router
- Axios
- CSS

Backend:
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication

Deployment:
- Frontend: Vercel
- Backend: Render

---

## Features

- User Signup
- User Login
- JWT based Authentication
- Protected Dashboard
- Display Logged-in User Information
- Logout Functionality
- Responsive UI

---

## Project Structure

src/
├── pages/
│ ├── Login.js
│ ├── Signup.js
│ └── Dashboard.js
├── api.js
├── App.js
└── index.js

yaml
Copy code

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/PriyanshiBajpai09/purplemerit-frontend.git
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Authentication Flow
User signs up or logs in

Backend returns a JWT token

Token is stored in localStorage

Protected routes are accessible only after login

Notes
Backend is deployed separately on Render

Frontend communicates with backend using REST APIs

Focus is on clean functionality and structure

Author
Priyanshi Bajpai
Backend Developer Intern Candidate – PurpleMerit

yaml
Copy code

---

### 🔹 STEP 4: **Save** the file  
- Ctrl + S press karo  
- README.md save ho gayi

---

# PART 3️⃣ – README.md **GitHub par push karni hai**

Terminal open karo **frontend folder ke andar** aur ye commands ek-ek karke chalao:

```bash
git add README.md
git commit -m "Add README file"
git push