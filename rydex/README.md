#  Ridesphere – Vehicle Booking and Management System

Ridesphere is a web-based **Vehicle Booking and Management System** designed to make vehicle searching, booking, payment, and user management easier and more convenient.

##  Features

*  User Registration and Login
*  Vehicle Browsing and Searching
*  Vehicle Booking
*  Online Payment Integration
*  Email Notifications
*  Location and Map Integration
*  Authentication and User Management
*  Booking Management
*  Real-time Communication using Socket.IO
*  Cloudinary Integration for Image Management

##  Technologies Used

### Frontend

* Next.js
* React
* TypeScript
* CSS

### Backend

* Next.js API Routes
* Node.js
* Socket.IO

### Database

* MongoDB

### Other Technologies

* Razorpay
* Cloudinary
* Nodemailer

##  Project Structure

```text
Ridesphere Vehicle Booking and Management System
│
├── rydex/
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── models/
│   │   └── redux/
│   ├── package.json
│   └── README.md
│
├── socketServer/
│   ├── models/
│   ├── index.js
│   └── package.json
│
└── .gitignore
```

##  How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/umrajahan/Ride-sphere-Vehicle-Booking-System.git
```

### 2. Open the project

```bash
cd Ride-sphere-Vehicle-Booking-System
```

### 3. Install dependencies for Rydex

```bash
cd rydex
npm install
```

### 4. Start the Next.js application

```bash
npm run dev
```

The application will normally run at:

```text
http://localhost:3000
```

### 5. Run the Socket Server

Open another terminal:

```bash
cd socketServer
npm install
node index.js
```

##  Environment Variables

For security, API keys and other secret information should be stored in environment files such as `.env.local`.

**Do not upload secret keys or passwords to GitHub.**

##  Project Objective

The main objective of Ridesphere is to provide a simple and efficient platform where users can search for vehicles, make bookings, manage their reservations, and complete payments through an online system.

##  Future Scope

* Mobile application
* Advanced vehicle recommendation system
* Admin analytics dashboard
* Improved payment options
* AI-based vehicle recommendations
* Advanced booking and notification system


##  Repository

GitHub Repository:

`https://github.com/umrajahan/Ride-sphere-Vehicle-Booking-System`
