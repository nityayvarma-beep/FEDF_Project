🏥 MediAssist - Smart Healthcare Management System
📌 Project Description
MediAssist is a modern healthcare management web application built using React + JavaScript + Vite. It helps users manage their health records, analyze symptoms, book appointments, estimate treatment costs, track recovery progress, access awareness resources, and interact with an AI-powered assistant.

This project is developed for the Front-End Engineering course and is designed to satisfy all CO1 - CO6 outcomes.

🛠️ Technologies Used
React JS
JavaScript (ES6+)
Vite
React Router DOM
Firebase Authentication
Google Login
Context API
CSS3
Local Storage
🎨 UI Theme
White Theme
Blue Accent Colors
Responsive Layout
Professional Healthcare Dashboard Design
📂 MediAssist Project Structure (React + JavaScript + Vite)
mediassist/
├── public/
|
├── src/
│   │
│   ├── assets/
│   │     ├── images/
│   │     ├── icons/
│   │     └── logos/
│   │
│   ├── components/
│   │     ├── Navbar/
│   │     │      └── Navbar.jsx
│   │     │
│   │     ├── Sidebar/
│   │     │      └── Sidebar.jsx
│   │     │
│   │     ├── Footer/
│   │     │      └── Footer.jsx
│   │     │
│   │     ├── Cards/
│   │     │      └── HealthCard.jsx
│   │     │
│   │     ├── Charts/
│   │     │      └── RecoveryChart.jsx
│   │     │
│   │     ├── AIAssistant/
│   │     │      └── ChatBot.jsx
│   │    
│   │     └── ProtectedRoute/
│   │            └── ProtectedRoute.jsx
│   │
│   ├── context/
│   │      └── AuthContext.jsx
│   │
│   ├── services/
│   │      ├── api.js
│   │      ├── firebase.js
│   │      └── data.j
│   │
│   ├── pages/
│   │
│   │    ├── Dashboard/
│   │    │      └── Dashboard.jsx
│   │    │
│   │    ├── Records/
│   │    │      └── Records.js
│   │    │
│   │    ├── Analysis/
│   │    │      └── Analysis.jsx
│   │    │
│   │    ├── Doctors/
│   │    │      └── Doctors.jsx
│   │    │
│   │    ├── Hospitals/
│   │    │      └── Hospitals.jsx
│   │    │
│   │    ├── Booking/
│   │    │      └── Booking.jsx
│   │    │
│   │    ├── Costs/
│   │    │      └── Costs.jsx
│   │    │
│   │    ├── Recovery/
│   │    │      └── Recovery.jsx
│   │    │
│   │    ├── Awareness/
│   │    │      └── Awareness.jsx
│   │    │
│   │    ├── Emergency/
│   │    │      └── Emergency.jsx
│   │    │
│   │    ├── Login/
│   │    │      └── Login.jsx
│   │    │
│   │    ├── Register/
│   │    │      └── Register.jsx
│   │    │
│   │    └── Profile/
│   │           └── Profile.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
├── .env
└── README.md
🏗️ Architecture Flow
User
↓
Google Login (Firebase)
↓
Auth Context
↓
Protected Routes
↓
Dashboard
↓
Health Modules
↓
Records
↓
Symptom Analysis
↓
Doctors
↓
Hospitals
↓
Appointments
↓
Cost Estimator
↓
Recovery Tracker
↓
Awareness Library
↓
Emergency Guide
↓
AI Assistant
🚀 Features
🏠 Dashboard
Health Summary
Upcoming Appointments
Notifications
Health Statistics
📋 Medical Records
Stores:

Blood Pressure
Heart Rate
Temperature
Blood Sugar
Allergies
Chronic Conditions
Emergency Contacts
🧠 Symptom Analyzer
Features:

Enter Symptoms
Possible Conditions
Confidence Percentages
Self-Care Tips
Emergency Warnings
🤖 AI Assistant
Features:

Ask health-related questions
Provides educational answers
Suggests next steps
Examples:

What are symptoms of diabetes?

How can I reduce blood pressure?

Foods that improve immunity?

When should I visit a doctor?
⚠️ Disclaimer:

AI Assistant provides educational information only and does not replace professional medical advice.

👨‍⚕️ Doctors
Features:

Doctor List
Specialization
Ratings
Availability Status
Badges:

🟢 Available Today

🟡 Tomorrow

🔴 Next Week
🏥 Hospitals
Features:

Nearby Hospitals
Emergency Hospitals
Specialty Filters
Distance Filters
📅 Appointments
Tabs:

Upcoming

Completed

Cancelled
Extra Features:

📧 Email Reminder

📅 Add To Calendar

🔔 Appointment Notifications
💰 Cost Estimator
Displays:

Government Cost
Standard Cost
Premium Cost
Insurance Savings
📈 Recovery Tracker
Features:

Daily Progress
Recovery Graph
Completion Percentage
Streak Tracking
📚 Awareness Library
Features:

Bookmark Articles
Save For Later
Share Articles
Levels:

🟢 Beginner

🟡 Intermediate

🔴 Advanced
🚨 Emergency Guide
Quick Actions:

📍 Share Live Location

📞 Call Emergency Contact

🏥 Nearest Hospital
🔐 Authentication
Firebase Authentication

Supports:

Google Login
Google Registration
Top Right Profile Displays:

Profile Picture
Name
Email Address
Logout Supported.

⚡ Performance Optimizations
Implemented:

Lazy Loading
Memoization
Component Reusability
State Colocation
Optimized Rendering
📖 Course Outcome Coverage
CO1: Foundations of Front-End Engineering
Implemented:

Component Architecture
Declarative UI
Unidirectional Data Flow
Rendering Abstraction
CO2: JavaScript Engineering
Implemented:

ES6+
Closures
Async/Await
Promise Handling
Modular Code Structure
CO3: React Component Engineering
Implemented:

Props
State
Hooks
Reusable Components
Controlled Forms
CO4: State Architecture & Async Engineering
Implemented:

Context API
Async Flow
Service Layers
Derived State
CO5: Routing & Accessibility
Implemented:

React Router DOM
Protected Routes
Form Validation
Accessibility Improvements
CO6: Build Systems & Deployment
Implemented:

Vite Build System
Environment Configurations
Production Build Optimization
Deployment Platforms:

Netlify
Vercel
▶️ Installation
Install Dependencies:

npm install
Run Development Server:

npm run dev
Open Browser:

http://localhost:5173
Create Production Build:

npm run build
Preview Production Build:

npm run preview
👨‍🎓 Project Information
Project Name:

MediAssist

Project Type:

Front-End Engineering Academic Project

Framework:

React + JavaScript + Vite

Purpose:

Engineering Project + PPT Viva Demonstration

Author:

Harshith
