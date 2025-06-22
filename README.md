# 💊 Meds Buddy Check

A role-based Medication Management app designed to help **patients** and **caretakers** track medications, view adherence, and manage routines efficiently. Built with **React**, **Node.js**, and **SQLite**, this app focuses on clarity, performance, and usability.

---

## 🧠 Project Overview

This application supports role-based dashboards for patients and caretakers, along with medication tracking features. It currently uses mock data and local state but is designed to evolve into a fully functional full-stack application with persistent storage and real-time features.

---

## ✨ Features

### ✅ Phase 1 
- **SQLite Authentication**:  
  - Secure login and signup for patients and caretakers.
- **Medication Management (CRUD)**:  
  - Add medications (name, dosage, frequency).  
  - Mark medications as taken for the day.  
  - View a list of medications.  
  - Display adherence percentage.
- **Dashboard Integration**:  
  - Real dashboard view (initially for one role) connected to SQLite backend.

### 🧩 Phase 2
- Real-time caretaker-patient updates.
- Adherence trend tracking.

### 🏆 Phase 3 
- Upload photos for medication proof.
- Deployment on Vercel/Netlify.

---

## 🛠️ Tech Stack

### Frontend
- React
- JavaScript
- React Query
- CSS

### Backend
- Node.js
- SQLite

---

## 📁 Current State of Codebase

- Role-based dashboard UI (patients/caretakers).
- Medication tracking with calendar view.
- Mock data for streaks and adherence logs.
- Non-functional interfaces:
  - Photo uploads
  - Notification settings
- All data is in-memory (no persistence yet).

---

