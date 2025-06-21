# 🌍 Real-Time Disaster Management System

A comprehensive real-time disaster response platform built with the **MERN Stack**, integrating **AI-powered location extraction**, **social media monitoring**, and **geospatial resource mapping** for effective emergency coordination.

🔗 **Live Site:** [Visit Now](https://disaster-response-coordination-plat-flame.vercel.app/disasters)

---

## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [API Documentation](#-api-documentation)
- [Usage Guide](#-usage-guide)
- [Real-time Features](#-real-time-features)
- [External Integrations](#-external-integrations)
- [Deployment](#-deployment)
- [Contact](#-contact)

---

## ✨ Features

### 🎯 Core Functionality
- Disaster CRUD operations with audit tracking
- Real-time updates via WebSockets
- AI-powered location extraction (Google Gemini)
- Geospatial mapping using PostGIS
- Real-time social media and official update monitoring

### 🔧 Advanced Features
- Supabase-based smart caching with TTL
- API rate limiting and security
- AI-based image authenticity verification
- Keyword-based alert priority classification
- Responsive UI (Tailwind CSS + React)

---

## 🛠 Tech Stack

**Backend**
- Node.js 18+, Express.js
- Supabase (PostgreSQL + PostGIS)
- Socket.IO, JWT Auth
- AI: Google Gemini API

**Frontend**
- React 18+, Tailwind CSS
- React Hooks, Framer Motion
- React Hot Toast, Lucide React Icons

**External Tools**
- Google Maps / Mapbox / OpenStreetMap
- Cheerio for Web Scraping
- Mock Twitter / Bluesky APIs

---

## 🏗 Architecture

```plaintext
[ React Frontend ] ↔ [ Express Backend ] ↔ [ Supabase DB ]
     ↕                     ↕                     ↕
[ WebSocket ]     [ AI + APIs + Caching ]    [ PostGIS ]
(https://github.com/user-attachments/assets/0871ddd8-5404-403f-ab33-71f73df6b44f)
(https://github.com/user-attachments/assets/32d26e7e-83d9-4385-ace0-d0209ad5b24a)
(https://github.com/user-attachments/assets/0ec689ca-dae2-43f6-ab51-110410f0720b)
(https://github.com/user-attachments/assets/d85e3785-727c-464d-ad0e-d670b5df3982)



## 📞 Contact

**Name:** Aman Verma  
**Roll No:** 2101233CS  
**Institutional Email:** [aman.2101233cs@iiitbh.ac.in](mailto:aman.2101233cs@iiitbh.ac.in)  
**Personal Email:** [amanverma740895@gmail.com](mailto:amanverma740895@gmail.com)  
**Live Project:** [Disaster Management System](https://disaster-response-coordination-plat-flame.vercel.app/disasters)

---
