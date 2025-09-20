# 🍬 Sweet Shop Management System

## 📖 Project Overview
The **Sweet Shop Management System** is a full-stack web application for managing sweet shop operations:  
- User authentication  
- Role-based dashboards (User/ Admin)  
- Sweet inventory management  
- Search, filter, purchase, and restock functionality  

This project was developed as part of the **Incubyte Assessment Kata**, focusing on **Test-Driven Development (TDD)**, clean coding, and responsible AI usage.

---

## 🔁 Test-Driven Development (TDD)
**TDD Workflow:** Red → Green → Refactor  

1. **Red:** Write a failing test  
2. **Green:** Implement minimum code to pass  
3. **Refactor:** Clean and optimize code while keeping tests passing  

**Benefits:**  
- Clean, readable code  
- Early bug detection  
- Confidence in code through automated tests  

---

## 🚀 Tech Stack

**Backend**  
- Node.js + Express + TypeScript  
- MongoDB (Mongoose ODM)  
- JWT Authentication + bcrypt  
- Jest + Supertest for testing  

**Frontend**  
- React (Vite + TypeScript)  
- Tailwind CSS for responsive UI  
- React Router for navigation  

---


---

## 🛠 Features

### Authentication
- Register: `POST /api/auth/register`  
- Login: `POST /api/auth/login`  
- JWT-based authentication  
- Role-based access (Customer / Admin)  

### Admin Sweet Management
- Add sweet: `POST /api/sweets`  
- Update sweet: `PUT /api/sweets/:id`  
- Delete sweet: `DELETE /api/sweets/:id`  
- Restock sweet: `POST /api/sweets/:id/restock`  

### Customer Features
- View all sweets: `GET /api/sweets`  
- Search / Filter sweets: `GET /api/sweets/search`  
- Purchase sweet: `POST /api/sweets/:id/purchase`  

---

## ⚡ API Endpoints

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| POST   | /api/auth/register | Register new user | Public |
| POST   | /api/auth/login | Login user | Public |
| POST   | /api/sweets | Add a sweet | Admin |
| GET    | /api/sweets | List all sweets | Auth |
| GET    | /api/sweets/search | Search sweets | Auth |
| PUT    | /api/sweets/:id | Update sweet | Admin |
| DELETE | /api/sweets/:id | Delete sweet | Admin |
| POST   | /api/sweets/:id/purchase | Purchase sweet | Auth |
| POST   | /api/sweets/:id/restock | Restock sweet | Admin |

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js >=18  
- MongoDB (local or cloud)

### Backend Setup
```bash
cd sweet-shop-backend
npm install
npm run dev      # Runs backend
npm test         # Run Jest tests


cd sweet-shop-frontend
npm install
npm run dev      # Runs frontend
---

Environment Variables

Backend (.env)

PORT=5000
MONGO_URI=<your-mongodb-url>
JWT_SECRET=<your_secret_key>


Frontend (.env)

VITE_API_URL=http://localhost:5000/api
🧪 Testing

Backend: Jest + Supertest
Frontend: Vitest

cd backend
npm test


Backend Test Screenshot:


Frontend Test Screenshot:


📸 Screenshots

Admin – Add Sweet:


Admin – Sweet Inventory:


Customer – Purchase Sweets:


Search & Filter:


TDD Flow – Red → Green → Refactor:


🤖 AI Usage

Tools: ChatGPT

Usage:

Generated boilerplate for backend controllers/routes/models

Created Jest + Vitest tests for TDD flow

Designed React components (Login, Signup, Dashboard)

Debugging and TypeScript fixes

Reflection:
AI accelerated boilerplate creation, reduced repetitive coding, and helped focus on business logic and architecture. All code was manually reviewed and tested.

🚀 Final Thoughts

This project demonstrates:

Test-Driven Development (TDD)

Clean, modular code design

Modern frontend UI with React + Tailwind

End-to-end integration between backend and frontend

🙏 Acknowledgements

Thank you Incubyte for this assessment and for encouraging TDD, clean coding, and AI-assisted development.

— Milan Vadhel


---

This is fully **terminal-friendly** and will render **perfectly on GitHub**.  

If you want, I can also make a **version with all headings, lists, and images perfectly aligned and pre-formatted for copy-paste**, including **TDD flow diagram using ASCII art** for terminal preview.  

Do you want me to do that?


## 🗂 Project Structure

