# 🚀 FlexiSlot – Smart Campus Slot Booking Platform

**FlexiSlot** is a full-stack web application developed to simplify on-campus slot reservations for students and staff. The platform enables users to securely book slots for **libraries, classrooms, and parking spaces** through an intuitive interface while providing administrators with efficient resource and booking management.

Built using **React.js**, **Spring Boot**, and **MySQL**, FlexiSlot offers secure authentication, real-time slot availability, seamless booking management, and a responsive user experience.

---

## ✨ Features

* 🔐 JWT-based User Authentication (Register, Login & Profile)
* 📅 Real-time Slot Booking & Availability
* 📚 Library, Classroom & Parking Reservations
* 🏠 Room and Resource Management
* 📖 User Booking History
* 📬 Contact Form for User Queries
* 📱 Fully Responsive User Interface
* 🎞️ Smooth Animations with Framer Motion
* ⚡ Secure REST API Integration
* 🛡️ Spring Security & JWT Authentication

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* React Router DOM
* Axios
* React Context API
* Framer Motion

### Backend

* Spring Boot
* Spring Security
* JWT Authentication
* Hibernate (JPA)
* MySQL

---

## 📂 Project Structure

```plaintext
FlexiSlot
│
├── frontend
│   ├── src
│   ├── public
│   ├── package.json
│   └── ...
│
├── backend
│   ├── src
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   ├── config
│   ├── utils
│   └── resources
│
├── screenshots
│
└── README.md
```

---

## 📸 Screenshots

### Home Page

<p align="center">
  <img src="screenshots/home.png" width="850"/>
</p>

### Booking Dashboard

<p align="center">
  <img src="screenshots/dashboard.png" width="850"/>
</p>

### Booking Page

<p align="center">
  <img src="screenshots/booking.png" width="850"/>
</p>

### Contact Page

<p align="center">
  <img src="screenshots/contact.png" width="850"/>
</p>

> **Note:** Replace the image names above with your actual screenshot names.

---

## ⚙️ Getting Started

### Prerequisites

* Java 17+
* Maven
* Node.js (v16+)
* MySQL

---

### Clone the Repository

```bash
git clone https://github.com/bleu-PANDA/FlexiSlot.git
cd FlexiSlot
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

### Backend Setup

Configure your MySQL database credentials inside:

```text
backend/src/main/resources/application.properties
```

Then run:

```bash
cd backend
mvn spring-boot:run
```

---

## 🌟 Future Improvements

* Admin Dashboard
* Email Notifications
* QR Code Based Check-In
* Payment Gateway Integration
* Calendar Integration
* Docker Deployment

---

## 👨‍💻 Contributors

* **Mehul Raj**
* **Arham Khan**

---

## 📄 License

This project was developed as part of an academic coursework project at **IIIT Lucknow**.
