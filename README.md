# PRESCRIPTO

> A prescription management application with a Backend API, User‑Facing Frontend, and Admin Dashboard.

---

## About the Project

Prescripto lets doctors create and manage prescriptions, patients view or request appointments, and pharmacists/admins oversee prescriptions and users via a dedicated dashboard. It’s divided into three parts:

1. **Backend API** (`backend/`)  
   - Node.js + Express serving REST endpoints  
   - MongoDB (via Mongoose) for users, doctors, prescriptions, and appointments  
   - File uploads (Multer + Cloudinary), payments (Stripe + Razorpay), JWT‑based authentication

2. **User‑Facing Frontend** (`frontend/`)  
   - React 18 bundled with Vite  
   - Tailwind CSS for styling  
   - Allows patients to browse doctors, book appointments, and view their history

3. **Admin Dashboard** (`admin/`)  
   - React 18 + Vite + Tailwind  
   - Enables admins to add doctors, manage appointments/users, and view payment reports

For detailed installation and running instructions, see the tutorial PDF:  
[How_To_Run_Project.pdf](./How_To_Run_Project.pdf)

---

## Tech Stack

- **Backend**  
  - Node.js ≥ 18.x, Express 4.x  
  - MongoDB (via Mongoose 8.x)  
  - bcrypt 5.x, jsonwebtoken 9.x (JWT), multer 1.x + Cloudinary 2.x (uploads)  
  - Stripe 16.x, Razorpay 2.x (payments)  
  - cors, dotenv, validator

- **Frontend (User & Admin)**  
  - React 18 + Vite  
  - Tailwind CSS  
  - React Router 6.x, Axios 1.x, React‑Toastify 10.x

- **Dev Tools**  
  - ESLint, Prettier, nodemon (backend development)

---
