# 🩺 Appointly

A **full-stack appointment booking platform** built with the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
Appointly simplifies scheduling and appointment management for users, doctors, and administrators — all within a clean, responsive web interface.

---

## 📖 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Roadmap & Future Enhancements](#roadmap--future-enhancements)
- [Contributing](#contributing)
- [License](#license)

---

## 🧠 About

**Appointly** provides a complete solution for online appointment management.  
Users can view available time slots, schedule appointments, and manage them in real time.  
Admins can manage users, doctors, and appointments through a dashboard with full control.

The platform is designed with a **modular architecture**, ensuring scalability and maintainability for real-world deployment.

---

## ✨ Features

- 🔐 **User Authentication** (Sign Up / Login / Logout)  
- 👥 **Role-Based Access Control** (Admin, Doctor, Patient)
- 📅 **Appointment Management**  
  - View, book, edit, or cancel appointments  
  - Real-time updates for users and admins  
- 🧾 **Admin Dashboard**  
  - Manage doctors, patients, and appointments  
  - View analytics and performance metrics  
- 📲 **Email or SMS Notifications** *(optional integration)*  
- 💻 **Responsive UI** built with React  
- 🔒 **Secure Authentication** using JWT & bcrypt  
- 🌐 RESTful API with Node.js + Express.js  
- 💾 Data stored in MongoDB (cloud/local)

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT, bcrypt |
| UI / Styling | Tailwind CSS (or Material-UI if used) |
| State Management | React Context / Redux (if used) |

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js and npm installed  
- MongoDB (Local or [MongoDB Atlas](https://www.mongodb.com/atlas))

### Steps

1. **Clone the repository**
   git clone https://github.com/piyush192004/Appointly.git
   cd Appointly

2. **Backend Setup**
   cd backend
   npm install

3.**Create a .env file in the backend repository**

4.**Start the backend server**
  npm run dev 
  
5.**Start the frontend server**
  cd ../frontend
  npm install
  npm start

---

# 🚀 Usage

## 👤 User / Patient
Register or log in → view available slots → book/edit/cancel appointments.

## 🩺 Doctor
Log in → manage schedule and appointments.

## 🧑‍💼 Admin
Log in → view analytics → manage users, doctors, and appointments.

---

# 🖼️ Screenshots

<img width="1919" height="948" alt="image" src="https://github.com/user-attachments/assets/ae9fef57-c4b0-4ed4-8082-6c5e9ebb8d54" />


### 🔹 Home / Landing Page
![Home Page](screenshots/home.png)

### 🔹 Booking Page
![Booking Page](screenshots/booking.png)

### 🔹 Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### 🔹 Responsive Mobile View
![Mobile View](screenshots/mobile.png)

---

# 🛠️ Roadmap & Future Enhancements

- 📆 Google Calendar / Outlook Integration
- 🔔 Push Notifications (Web + Mobile)
- 🧾 Appointment Analytics and Reports
- 🌙 Dark / Light Mode Toggle
- 🧑‍💻 Multi-Tenant Support for Clinics / Organizations

---

# 🤝 Contributing

Contributions are welcome!  
To contribute:

1. Fork this repository  
2. Create a new branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

---

# 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute this project.
