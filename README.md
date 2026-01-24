# Smart Campus Optimizer

🚀 **Live Demo:** [https://smartcampusoptimizer.netlify.app/](https://smartcampusoptimizer.netlify.app/)

📦 **GitHub Repository:** [https://github.com/Karthisha25/smartcampusoptimizers](https://github.com/Karthisha25/smartcampusoptimizers)

---

## 📌 Overview

Smart Campus Optimizer is a web-based application designed to reduce queue congestion, improve time management, and optimize campus services. It leverages AI-assisted crowd prediction and waiting time estimation to help students make smarter decisions while accessing campus facilities.

The project focuses on building an **AI-ready, data-driven, and scalable campus service optimization system**.

---

## ❗ Problem Statement

Students often face long waiting times and overcrowding at campus services such as:

* Canteen
* Library
* Administration Office
* Examination Cell

This leads to time wastage, poor scheduling, and reduced overall efficiency.

---

## 💡 Proposed Solution

Smart Campus Optimizer predicts **crowd levels** and **estimated waiting times** based on:

* Selected campus service
* Day of the week
* Time slot

This enables students to plan visits during less crowded periods and reduce physical queues.

---

## ✨ Features

* AI-based crowd level prediction
* Estimated waiting time display
* Smart canteen pre-ordering interface
* Library seat availability and slot booking
* Administration office appointment booking
* Examination cell request tracking
* Firebase Firestore integration for prediction history
* Responsive and user-friendly UI
* Live deployment on Netlify

---

## 🧠 Google Technologies Used

* **Google Gemini API** – AI-based crowd and waiting time prediction
* **Google AI Studio** – API key generation and model access validation
* **Firebase Firestore** – Storage of prediction history and usage data

---

## 🛠️ Tech Stack

* **Frontend:** React, TypeScript, Vite
* **Styling:** CSS
* **AI:** Google Gemini API
* **Database:** Firebase Firestore
* **Hosting:** Netlify
* **Version Control:** GitHub

---

## 🔄 System Workflow

User Input → Prediction Logic → Gemini AI → Firestore Storage → UI Display

---

## ▶️ Run Locally

```bash
npm install
npm run dev
```

Create a `.env` file in the root directory and add:

```env
VITE_GEMINI_API_KEY=your_api_key_here
```

---

## 🌐 Deployment

The project is deployed on **Netlify** using Vite build output.

🔗 Live URL: [https://smartcampusoptimizer.netlify.app/](https://smartcampusoptimizer.netlify.app/)

---

## 🔮 Future Scope

* Improve AI prediction accuracy using long-term historical and seasonal data
* Expand to additional campus services
* Add smart notifications and alerts
* Integrate secure online payment options
* Support multiple campuses and hostels

---

## 👥 Team Contributions

* UI and frontend development
* AI prediction logic integration
* Firebase Firestore integration
* Deployment and documentation

---

## ✅ Conclusion

Smart Campus Optimizer delivers an AI-driven and data-centric solution to campus service management. By reducing congestion and improving planning, it enhances efficiency and overall student experience across campus facilities.
