# 📬 Newsletter Management System

A full-stack **Newsletter Management System** with a role-based workflow for article submission, review, approval, and newsletter generation.

The system integrates **AI-powered article generation using Ollama (Mistral)** and follows a clean, scalable architecture.

---

## 🚀 Features

- 🔐 Role-based access control (Admin, Approver, User)
- 📝 Article submission system
- ✅ Article approval workflow
- 🧩 Drag-and-drop newsletter builder
- 📄 Newsletter PDF generation
- 🤖 AI article generation (Ollama - Mistral)
- 🖼 Media upload support

---

## 🏗 System Architecture
User Browser
│
▼
React Frontend (Tailwind CSS)
│
▼
Express.js API (REST Layer)
│
├── Authentication (JWT + Role-Based Access)
├── Business Logic (Controllers & Services)
├── File Storage (Uploads)
├── MySQL Database
└── Ollama AI (Mistral via API)


---

## 🧠 Architecture Overview

- **Frontend (React + Tailwind)**  
  Handles UI and API communication.

- **Backend (Node.js + Express)**  
  Manages APIs, authentication, and business logic.

- **Authentication**  
  JWT-based authentication with role-based access control.

- **Database (MySQL)**  
  Stores users, articles, workflows, and newsletters.

- **File Storage**  
  Handles media uploads and static files.

- **AI Integration (Ollama - Mistral)**  
  Generates article content via backend API calls.

---

## ⚙️ Workflow

### 👤 User
- Submit articles  
- Upload media  
- Track article status  

### 🧑‍💼 Approver
- Review articles  
- Approve / Reject / Return with comments  

### 🧑‍💻 Admin
- Manage articles  
- Select approved articles  
- Arrange layout (drag-and-drop)  
- Generate PDF newsletters  

---

## 🛠 Tech Stack

**Frontend**
- React.js
- Tailwind CSS
- Axios

**Backend**
- Node.js
- Express.js

**Database**
- MySQL

**AI**
- Ollama (Mistral)

---

## 📂 Project Structure
newsletter-management-system/
│
├── backend/
│ ├── config/
│ ├── middleware/
│ ├── models/
│ ├── controllers/
│ ├── routes/
│ ├── services/
│ ├── uploads/
│ └── server.js
│
├── frontend/
│ ├── src/
│ ├── components/
│ ├── pages/
│
├── .gitignore
├── package.json
└── README.md


---

## 🔐 Security

- JWT Authentication  
- Role-based authorization  
- Protected API routes  

---

## 🤖 AI Integration

- Uses **Ollama (Mistral model)**  
- Generates article drafts based on prompts  
- Helps users create content faster  

---

## 🚀 Future Enhancements

- Email newsletter distribution  
- Cloud storage (AWS / Azure)  
- Real-time notifications  
- Analytics dashboard  

---
