🌆 CitizenCare — Smart Civic Grievance Platform

🏆 Hackathon Runner-Up Project

CitizenCare was recognized as a Runner-Up in a national-level hackathon for building a complete smart-city grievance management system with geospatial intelligence, administrative dashboards, and real-time civic issue tracking.

The platform demonstrates a full Citizen → Admin → Officer workflow designed to improve municipal transparency and response efficiency.

🚀 Overview

CitizenCare is a full-stack Smart City Grievance Management Platform that enables citizens to report civic issues and allows municipal authorities to resolve them efficiently through a powerful data-driven command center.

The system integrates geospatial mapping, complaint lifecycle tracking, officer task assignment, and municipal analytics into one unified platform.

🧠 Key Features
🧍 Citizen Portal

Citizens can easily report civic issues and monitor progress.

Features:

📍 Map-based complaint reporting

📷 Upload photo evidence

📝 Detailed grievance descriptions

📊 Complaint tracking dashboard

🗺 Complaint hotspot visualization

⭐ Feedback after resolution

🏛 Admin Command Center

A powerful dashboard designed for municipal authorities.

Capabilities:

Monitor all complaints across the city

Assign complaints to officers

Manage departments and personnel

Analyze complaint trends

Track resolution performance

Identify civic infrastructure hotspots

👮 Officer Task Management

Officers receive and resolve complaints assigned by administrators.

Features:

Assigned complaint dashboard

Status updates and progress tracking

Resolution proof uploads

Workload monitoring

Performance analytics

🗺 Geospatial Intelligence

CitizenCare integrates interactive map-based monitoring to visualize civic issues across the city.

Capabilities:

Complaint location pinning

Real-time complaint markers

Complaint density heatmaps

Region-wise monitoring

Infrastructure hotspot detection

Built using:

Leaflet + OpenStreetMap

🔄 Complaint Lifecycle

The system follows a structured grievance resolution workflow.

Citizen submits complaint
        ↓
Complaint stored in database
        ↓
Admin reviews complaint
        ↓
Admin assigns officer
        ↓
Officer resolves issue
        ↓
Citizen receives update
        ↓
Citizen submits feedback
🏗 System Architecture
Frontend (React + TailwindCSS)
        ↓
Backend API (Node.js + Express)
        ↓
MongoDB Database
        ↓
Geospatial Engine (Leaflet + OpenStreetMap)
        ↓
Analytics & Monitoring Dashboards
⚙️ Technology Stack
Frontend

React.js

TailwindCSS

Framer Motion

React Router

Leaflet.js (Maps)

Backend

Node.js

Express.js

JWT Authentication

Database

MongoDB

Geospatial Indexing (2dsphere)

📊 Platform Modules
Module	Description
Citizen Portal	Submit and track grievances
Admin Dashboard	Manage complaints and assign officers
Officer Portal	Handle assigned complaints
Analytics Engine	Complaint statistics and trends
Geospatial Engine	Complaint mapping and hotspot detection
📸 Platform Preview
Citizen Dashboard

Admin Command Center

Complaint Map

(Add your screenshots inside a screenshots folder in the repository.)

📦 Installation

Clone the repository

git clone https://github.com/Abhinay-12-k/citizencare.git
cd citizencare
Backend Setup
cd backend
npm install

Create a .env file

MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_secret

Run backend server

npm run dev
Frontend Setup
cd frontend
npm install
npm run dev
🔑 Demo Credentials
Role	Email	Password
Admin	admin@city.gov
	password123
Citizen	alex@gmail.com
	password123
Officer	john@pwd.gov
	password123
🎯 Example Demo Workflow

Citizen reports a civic issue using map-based location.

Complaint is stored in the system.

Admin reviews and assigns it to an officer.

Officer resolves the issue and uploads proof.

Citizen receives update and provides feedback.

🔮 Future Enhancements

AI-based complaint categorization

Predictive infrastructure maintenance

Mobile application

Smart city IoT integrations

Automated complaint prioritization

🤝 Contributing

Contributions are welcome.

Steps:

Fork the repository
Create a feature branch
Commit your changes
Submit a pull request
📜 License

MIT License.

👨‍💻 Author

Abhinay Kamagonda
