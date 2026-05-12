# 🎧📊 Vibe-Fanalyze Platform

Vibe-Fanalyze is a multi-sport analytics ecosystem that combines
data engineering, predictive modeling, betting math, and interactive
dashboards into one unified platform.

This repository serves as the **platform entry point** that documents,
connects, and orchestrates the Vibe-Fanalyze services.

---

## 🧩 Platform Components

### 🧠 Backend Core (Analytics & ML)
**Repo:** vibe-fanalyze-core  
- Multi-sport analytics (NFL, NBA active)
- Prediction engine + Kelly Criterion
- AI-powered chat assistant (VibeBot)
- MySQL + MongoDB hybrid storage
- Modular FastAPI architecture

👉 https://github.com/yourname/vibe-fanalyze-core

---

### ⚡ Backend API (Production-Style)
**Repo:** vibe-fanalyze-api  
- Clean FastAPI service
- JWT authentication
- CRUD for users, teams, players, games
- Predictable, documented endpoints

👉 https://github.com/yourname/vibe-fanalyze-api

---

### 📊 Dashboard (Visualization Layer)
**Repo:** vibe-fanalyze-dashboard  
- Streamlit-based analytics UI
- Consumes FastAPI endpoints
- Interactive exploration of teams, players, games

👉 https://github.com/yourname/vibe-fanalyze-dashboard

---

## 🏗️ Architecture Overview
[ Streamlit Dashboard ]
|
v
[ FastAPI API Layer ]
|
v
[ Analytics Core / ML / Kelly Engine ]
|
-----------------
|               |
[ MySQL ]       [ MongoDB ]

---

## 🏆 Supported Leagues

- ✅ NFL
- ✅ NBA
- 🔧 MLB
- 🔧 WNBA
- 🔧 NHL
- 🔧 MLS
- 🔧 UFC

---

## 🚀 Future Plans

- Sportsbook odds integration
- Real-time data ingestion
- React production frontend
- Cloud deployment (Docker + CI/CD)

See ROADMAP.md for details.

