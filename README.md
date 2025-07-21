# Doctor Appointment Booking System

A full-stack doctor appointment system where Admins can manage doctors and users, Doctors can view appointments and upload prescriptions, and Patients can book appointments online. Built with **React**, **Node.js**, **MongoDB**, and **Cloudinary**.


## 📌 Features

### 👤 User Roles
- **Admin**: Manage doctors, users, and view all appointments
- **Doctor**: View booked appointments, upload prescriptions
- **User**: Book appointments, view prescription history

### 🛠️ Functionalities
- JWT-based authentication
- Role-based access control
- Appointment booking and tracking
- Secure image upload via Cloudinary (e.g., prescriptions)
- Protected routes with separate middleware
- Password hashing with bcrypt
- Responsive UI with Tailwind CSS

---

## 🧑‍💻 Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router DOM
- Axios

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- Cloudinary for image uploads
- Multer (file upload handling)
- bcrypt (password hashing)
- jsonwebtoken (JWT)
- dotenv
- cors

---

## ⚙️ Project Setup

### 🚀 Frontend

```bash
cd frontend
npm install
npm start
