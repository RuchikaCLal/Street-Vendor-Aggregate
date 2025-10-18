# 🌍 Street Vendor Aggregate

**FindMyCart** is a community-driven platform designed to bridge the gap between local street vendors and nearby customers.  
The project helps vendors gain visibility and helps users easily discover and support local businesses through map-based listings, reviews, and digital vendor profiles, all using open-source and free tools.

## 🚀 Project Overview

Street vendors often face challenges such as limited visibility, lack of digital presence, and inconsistent customer flow.  
This platform aims to solve these issues by:

- Providing vendors with a **free digital storefront** (profile, location, and UPI QR).
- Helping customers **find and connect** with nearby vendors using a simple map interface.
- Enabling community growth through **reviews, ratings, and local recommendations.**

This project is being developed as part of a college initiative to create **socially impactful tech solutions** using open-source technologies.


---


## 🧩 Folder Structure

```text
street-vendor-aggregate/
├── frontend/      → React + Vite app (UI, map, registration, reviews)
├── backend/       → Firebase / Express setup (APIs, Firestore, Storage)
├── .gitignore     → Ignored files (node_modules, env)
└── README.md      → Project overview and documentation
```


## ⚙️ Tech Stack

| Category | Technology Used |
|-----------|-----------------|
| **Frontend** | React (Vite), Leaflet.js, OpenStreetMap |
| **Backend** | Firebase (Firestore, Auth, Storage) / Node.js (optional APIs) |
| **Design** | Figma, Canva |
| **Hosting** | Vercel (frontend) / Firebase Hosting (optional for backend) |
| **Version Control** | Git + GitHub |
| **Testing** | Manual testing, Chrome DevTools |


## Team Members

- **Ruchika C. Lal** – Product Lead & Designer  

- **Jayashree G** – Backend Developer   

- **Vismaya Lokesh** – Map & Testing Engineer  



# ⚙️ Setup Instructions
Follow the steps below to set up and run the project locally.

### 🖥️ 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/street-vendor-aggregate.git
cd street-vendor-aggregate

```
### 🖥️ 2. Frontend Setup
The frontend folder contains the user interface built using **React + Vite**.
```bash
cd frontend
npm install
npm run dev
```

### 🖥️ 3. Backend Setup
The backend folder handles data storage, authentication, and APIs using Firebase / Express.
```bash
cd backend
npm install
node index.js
```
