# 🌐 National Service Scheme (NSS) IIIT–Naya Raipur — Dynamic Website

This project is a **dynamic website for the NSS (National Service Scheme) Unit of IIIT–Naya Raipur**, designed to showcase activities, initiatives, and achievements while providing administrators a secure way to manage photo galleries and content dynamically.

---

## 📘 Project Overview
The NSS website serves as the official digital presence for the IIIT–NR NSS Unit. It highlights various community initiatives, events, and achievements while ensuring a dynamic and easily maintainable photo gallery system through an **Admin Dashboard**.

### 🎯 Objectives
- Provide a **modern, responsive website** for the NSS unit.  
- Enable **admins to upload/manage photos and descriptions** dynamically.  
- Reflect the **spirit of community service, technology, and youth engagement**.  

---

## 🧩 Features

### 🖥️ Frontend (Public Website)
- **Responsive Home Page** with hero slideshow (auto-updated via backend).  
- **Dynamic Photo Gallery** categorized by activity type (Education, Health, Environment, Community).  
- **Initiatives & Achievements Sections** displaying NSS projects and recognitions.  
- **AI Assistant Chatbox** for interactive queries (static demo version).  
- **Contact Section** with integrated map and official contact info.  
- **Print-friendly Achievements Section** for reports and documentation.  

### 🔐 Admin Panel (`admin.html`)
- **Password-Protected Dashboard** (local demo password: `nssadmin123`).  
- **Photo Upload Form**: Add title, description, and category (gallery/logo/etc.).  
- **Photo Management**: View uploaded photos, delete entries dynamically.  
- **Real-time Updates**: Changes made in admin panel reflect immediately on the main site.  

---

## ⚙️ Technology Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla JS, AOS for animations) |
| **Styling** | Custom CSS with gradients, blur effects, and responsive grid layouts |
| **Backend (for dynamic data)** | Node.js + Express.js (API endpoints: `/api/photos`, `/api/upload`, `/api/delete`) |
| **Database** | MongoDB (for storing image metadata and paths) |
| **Hosting (suggested)** | GitHub Pages for static frontend + Render/Heroku for backend API |

---

## 🧰 Folder Structure

```
project/
│
├── index.html          # Main NSS website (frontend)
├── admin.html          # Admin dashboard (photo upload & management)
├── styles/             # CSS stylesheets
├── assets/             # Static assets (logos, icons, placeholders)
└── server/             # Node.js backend (API & database integration)
```

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/nss-iiitnr-website.git
cd nss-iiitnr-website
```

### 2. Setup Backend (Optional)
If you want dynamic uploads:
```bash
cd server
npm install
npm start
```
Ensure MongoDB and server run at `http://localhost:5000`.

### 3. Run Frontend
Open `index.html` directly or host via:
```bash
npx live-server
```
Access it at `http://localhost:8080`.

---

## 🧠 AI Integration (Experimental)
The **AI Assistant** provides basic static responses and can be extended using OpenAI API for:
- Answering NSS-related queries.
- Assisting with event planning.
- Summarizing past initiatives dynamically.

---

## 👥 Contributors
- **Aditya Tyagi** – Developer & Designer  
- **Krishnanand Vishwakarma** – Program Officer (NSS, IIIT–NR)  
- **IIIT–Naya Raipur NSS Volunteers** – Content and media contributors  

---

## 📄 License
This project is developed for **academic and institutional purposes** at IIIT–Naya Raipur.  
© 2025 National Service Scheme – IIIT–Naya Raipur Unit. All rights reserved.

---

**“Not Me, But You” — NSS Motto**
