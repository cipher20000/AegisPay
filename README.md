<div align="center">

<img src="./assets/logo.png" alt="AegisPay Logo" width="90"/>

# 🛡️ AegisPay  
### AI-Assisted Full-Stack Fraud Detection Dashboard  
*(React + FastAPI + PostgreSQL + scikit-learn)*  

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-success?logo=fastapi)
![Python](https://img.shields.io/badge/Python-ML-blue?logo=python)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-lightblue?logo=postgresql)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

</div>

---

## 🧠 Overview
**AegisPay** is an AI-powered fraud detection dashboard for fintech and banking platforms.  
It uses **machine learning** and **real-time analytics** to detect and prevent fraudulent transactions with transparency and trust.

> 💬 *AI + Trust + Transparency in Payments.*

---

## 🚀 Features
- ⚙️ **AI Fraud Detection Engine** — Logistic Regression, Random Forest, XGBoost  
- 📊 **Interactive Dashboard** — React + Tailwind UI  
- 💾 **PostgreSQL Database** — Store transactions & risk logs  
- 🔍 **FastAPI Backend** — ML inference and analytics  
- 📈 **Real-Time Visualizations** — Fraud probability, risk maps  
- 🔐 **Smart Risk Scoring** — AI-based probability per transaction  


### 🔐 Login Page
![Login](https://github.com/cipher20000/AegisPay/blob/2d1f85b7547114ae0dee4df9801b008cdb826764/login.png?raw=true)

### 📊 Dashboard
![Dashboard](https://github.com/cipher20000/AegisPay/blob/2d1f85b7547114ae0dee4df9801b008cdb826764/dashboard.png?raw=true)


*(Save these images in an `/assets` folder inside the repo.)*

---

## ⚙️ Tech Stack
**Frontend:** React.js, TypeScript, TailwindCSS, Recharts  
**Backend:** FastAPI, scikit-learn, pandas, NumPy  
**Database:** PostgreSQL (via SQLAlchemy)  
**Deployment:** Docker + CI/CD ready  

---

## 🧩 Quick Start

```bash
# Clone repo
git clone https://github.com/cipher20000/AegisPay.git
cd AegisPay

# Backend setup
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

# Frontend setup
cd frontend
npm install
npm run dev
