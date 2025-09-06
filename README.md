# Whiteboard Project

This is a full-stack whiteboard collaboration application with a backend built using Node.js and Express, and a separate frontend (inside frontend1.zip).

---

## Project Structure

Whiteboard_project/
├── authMiddleware.js
├── canvasController.js
├── canvasModel.js
├── canvasRoutes.js
├── config.js
├── frontend1.zip # Frontend code (React or static site)
├── package.json
├── package-lock.json
├── server.js # Entry point of the backend server
├── userController.js
├── userModel.js
├── userRoutes.js
├── vercel.json # Vercel deployment config (optional)
└── .env # Environment variables (not included)

yaml
Copy
Edit

---

## ⚙ Backend Setup (Express + MongoDB)

### 🛠 Install dependencies

```bash
npm install
Start the server
bash
Copy
Edit
node server.js
⚠ Make sure to configure your .env file with necessary values like MongoDB URI, JWT secret, etc.

API Endpoints
User Routes (/api/users)
POST /register – Register a new user

POST /login – Login a user

GET /me – Get current user (with token)
 Canvas Routes (/api/canvas)
POST /create – Create a canvas session

GET /:id – Get canvas data by ID

PUT /:id – Update canvas data

Frontend
The frontend is located in frontend1.zip.
Please extract it and refer to the README inside for running instructions.

 Technologies Used
Backend: Node.js, Express

Authentication: JWT, Middleware

Database: MongoDB + Mongoose

Frontend: (Assumed React or HTML/JS — check frontend1.zip)

Deployment: Can be deployed on Vercel, Render, or Heroku

![image](https://github.com/user-attachments/assets/66852b18-8e71-4f56-a98f-da5731646693)
