# 📂 Portfolio Builder App

Portfolio Builder App is a full-stack web application that helps users—students, freelancers, and job seekers—create and manage professional portfolios easily. Users can securely register, add personal and project details, and choose from pre-designed responsive templates to generate a live portfolio website.

The application ensures secure authentication, dynamic portfolio previews, image uploads, and a fully responsive design across devices. Data is stored in MongoDB Atlas, and files are managed securely through the backend.
---

## ✨ Features

### 🔐 Authentication & Authorization
- Secure **JWT-based authentication** for users and admins.
- Passwords encrypted using **bcrypt**.
- Role-based access control and protected API routes.

### 🖊 Portfolio Management
- Add **personal details**, education, experience, and skills.
- Upload and manage **project details** with images.
- Live preview of portfolio before publishing.
- **Search and filter** functionality for projects.

### 🖼 Image Handling
- Upload profile and project images.
- File storage handled via backend using **Multer**.

### 📱 Responsive Design
- Mobile-first UI.
- Optimized for desktop, tablet, and mobile devices.

---

## 🛠 Tech Stack

### **Frontend**
- **React.js** with **TypeScript**
- **TanStack Router** for routing
- **Context API + React Hooks** for state management
- **Tailwind CSS** for styling
- **Lucide React** for icons

### **Backend**
- **Node.js** with **Express.js** and **TypeScript**
- **MongoDB** with **Mongoose**
- **Multer** for file uploads
- **bcrypt.js** for password hashing
- **jsonwebtoken** for JWT authentication

---

## Installation
To run this project locally, follow these steps:

Clone the repository:
  git clone https://github.com/your-username/resume-builder.git
  Install dependencies for both frontend and backend:

cd client
npm install
cd ../server
npm install

Set up environment variables:

Create a .env file in the backend directory.
Add your MongoDB connection URI, JWT secret, and any other necessary variables.

Start the development servers:
## Start backend server (runs on http://localhost:5000)
cd server
npm start

## Start frontend development server (runs on http://localhost:5173)
cd client
npm start
Open your browser and navigate to http://localhost:3000 to view the application.


