Smart Campus Optimizer
Live Demo:
https://smartcampusoptimizer.netlify.app/
GitHub Repository:
https://github.com/Karthisha25/smartcampusoptimizers
Project Overview
Smart Campus Optimizer is a web-based application designed to reduce queue congestion, improve time management, and optimize campus services. The system provides AI-assisted crowd prediction and waiting time estimation to help students make better decisions while accessing campus facilities.
The platform focuses on building an AI-ready, data-driven, and scalable campus service optimization system.
Problem Statement
Students face long waiting times and overcrowding at campus services such as canteen, library, administration office, and examination cell, leading to time wastage and reduced efficiency.
Proposed Solution
Smart Campus Optimizer predicts crowd levels and waiting times based on selected service, day, and time, helping students choose less crowded time slots and reduce physical queues.
Features
AI-based crowd level prediction
Estimated waiting time display
Smart canteen pre-ordering interface
Library seat availability and slot booking
Administration office appointment booking
Examination cell request tracking
Firebase Firestore integration for storing prediction history
Responsive and user-friendly UI
Live deployment on Netlify
Google Technologies Used
Google Gemini API – AI-based crowd and waiting time prediction
Google AI Studio – API key generation and model access validation
Firebase Firestore – Storage of prediction history and usage data
Tech Stack
Frontend: React, TypeScript, Vite
Styling: CSS
AI: Google Gemini API
Database: Firebase Firestore
Hosting: Netlify
Version Control: GitHub
System Workflow
User Input → Prediction Logic → Gemini AI → Firestore Storage → UI Display
How to Run Locally
npm install
npm run dev
Create a .env file and add:
VITE_GEMINI_API_KEY=your_api_key_here
Deployment
The project is deployed on Netlify using Vite build output.
Live URL:
https://smartcampusoptimizer.netlify.app/
Future Scope
Improve AI prediction accuracy using long-term historical and seasonal data
Expand to more campus services using the same framework
Add smart notifications and alerts
Integrate secure online payment options
Support multiple campuses and hostels
Team Contributions
UI and frontend development
AI prediction logic integration
Firebase Firestore integration
Deployment and documentation
Conclusion
Smart Campus Optimizer provides an AI-ready and data-driven approach to campus service optimization, improving efficiency and reducing congestion across campus facilities.
