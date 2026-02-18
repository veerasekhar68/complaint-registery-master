#  ResolveNow – Online Complaint Registration & Management System

##  Project Overview

ResolveNow is a full-stack web application designed to streamline complaint registration, tracking, and resolution processes within organizations.

The system enables users to submit complaints, track their status, and communicate with administrators. Admins can manage users, assign complaints, update statuses, and monitor resolution progress.

---

##  Key Features

###  User Features
- User Registration & Login
- Submit Complaints
- Track Complaint Status
- View Complaint History
- Update Profile

###  Admin Features
- Admin Authentication
- View All Complaints
- Assign Complaints
- Update Complaint Status
- Manage Users
- View Dashboard Analytics

---

##  System Architecture

Frontend → React.js  
Backend → Express.js (Node.js)  
Database → MongoDB  
API Communication → REST APIs  

```
Client (React)
     ↓
Express Server (Node.js)
     ↓
MongoDB Database
```

---

##  Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- Mongoose
- REST API
- JavaScript
- HTML/CSS

---

##  Project Structure

```
ResolveNow/
│
├── client/          # React Frontend
├── server/          # Express Backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── index.js
├── package.json
└── README.md
```

---

##  Installation & Setup

### 1️ Clone Repository

```
git clone https://github.com/YOUR-USERNAME/ResolveNow.git
cd ResolveNow
```

### 2️ Install Backend Dependencies

```
cd server
npm install
```

### 3️ Install Frontend Dependencies

```
cd ../client
npm install
```

### 4️ Configure Environment Variables

Create `.env` file inside server folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 5️ Run Backend

```
cd server
npm start
```

### 6️ Run Frontend

```
cd client
npm start
```

Application will run at:

```
http://localhost:3000
```

---

##  Security Features

- Role-Based Access Control
- Secure Password Handling
- API Validation
- Protected Routes
- JWT Authentication (if implemented)

---

##  Future Enhancements

- Email Notifications
- Complaint Category Analytics
- Real-time Status Updates
- Admin Performance Reports
- Cloud Deployment
- Mobile Responsive UI

---

##  Use Case

This system can be used in:

- Colleges
- Corporates
- Municipal Services
- Customer Support Systems
- Government Portals

---

##  Author

**Veera Shekar Achari**  
Full-Stack Developer | MERN Stack | Cybersecurity Enthusiast  

---

##  License

This project is developed for academic and portfolio purposes.

Developed by:
- D. Siva Sankar Reddy (Team Leader)
- S. Munendra
- K. Veerasekhar Achari
- D. Chandrasekhar
