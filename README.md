# TFI_CAMPUS_HANYANG_25Spring_REPACT

## Re:Fact

An easy and fun waste sorting game, **Re:Fact**, designed to help protect the environment.

This project is a **gamification-based educational solution** developed in collaboration with **Refeely**, an eco-friendly packaging company.  
It aims to promote correct waste separation and recycling practices, starting with paper cartons.

---

## 🌱 Project Overview

Re:Fact was inspired by the low recycling rate of paper cartons.  
The project goes beyond simple information delivery — it helps users **learn and practice separation methods through gameplay**.

---

## 💡 Problem Definition

- **Paper carton recycling rate:** 13% (compared to the overall rate of 86.8%)
- **Causes:**
  - Lack of awareness of correct separation and recycling value
  - Complex disposal process and low motivation
  - Insufficient collection infrastructure

These issues are common across different types of waste, not just paper cartons.

---

## 🎮 Solution: The Re:Fact Game

### 1. Core Features
- Waste sorting gameplay (5 categories: paper cartons, plastic, cans, etc.)
- Missions to teach pre-processing actions (e.g., washing before disposal)
- Quiz rounds to check recycling knowledge

### 2. Gameplay Flow
1. Use arrow keys to sort waste.  
2. For items requiring pre-treatment, input commands to learn correct handling.  
3. Check your performance and earn points on **My Page**.

### 3. Point System
- Points awarded based on difficulty level and completion time.  
- Points can be exchanged for real Refeely Mall products.  
- Scan product **QR codes** to launch the game and earn bonus points.

### 4. Target Users & Use Scenarios
- **Refeely customers:** Scan QR → Play → Earn points → Practice eco-friendly habits.  
- **Elementary to high school students:** Use in classrooms → Learn → Encourage household participation.

---

## 🔗 Partnerships & Integrations

- **Refeely Mall:** Convert in-game points into real product purchases.  
- **Schools / Educational Institutions:** Utilize the game as sustainability education content.

---

## 📈 Impact & Expected Outcomes

- **75.5%** of users learned new information.  
- **77.6%** reported improved eco-friendly behavior.  
- Among low-awareness users, **96.3%** showed increased willingness to act.

### Three-Year Goals
- Increase paper carton recycling rate from **13% → 14% (+1pp)**  
- Save approximately **₩123 million** in recycling costs  
- Reach **90,000 households** through environmental education

---

## 🎮 Play the Game

[https://funny-pasca-8573bf.netlify.app/](https://funny-pasca-8573bf.netlify.app/)

---

## 🧪 User Testing Results

| Category | Percentage |
|-----------|-------------|
| Learned new information through gameplay | 75.5% |
| Helped behavioral change in daily life | 77.6% |
| Behavioral change in low-awareness users | 96.3% |

> Positive responses were also confirmed through interviews with middle school students and parents.

---

## 🛠️ Team Members

| Name | Role | Major | Interests |
|------|------|--------|-----------|
| Ho-won Lee | PM | Electrical Engineering | AI-based Social Services |
| Nam-ryeol Kim | FE | Future Mobility | Autonomous Driving |
| Seung-hwan Shim | BE | Future Mobility | Computer Vision |
| Do-yeon Park | FE | Mathematics | Data Mining |
| Hee-jun Lee | UI/UX | Economics & Finance | Social Innovation Consulting |

---

## 📎 Appendix

### Point Calculation
- **Score = Round score (100–300 by difficulty) + Time bonus**  
- **Time bonus = (Average 60s / Actual time) × Score**

### Impact Estimation
- 30,000 elementary households → approx. **240 tons of recyclable waste** recovered annually  
- Equivalent to **+0.34%p** of total paper carton production (70,000 tons)  
- Long-term goal: **+1%p recycling rate increase**

---

⚙️ Backend

- **Framework:** FastAPI – A fast and modern Python web framework for RESTful APIs  
- **Routing & Authentication:** OAuth2-based JWT system for user registration, login, and access control  
- **Business Logic:**
  - Manage user registration and login
  - Record and retrieve game scores  
- **Database:** SQLite – Lightweight local database storing user and score data  
- **Deployment:** AWS Lightsail – Deployed on an Ubuntu-based instance  
- **Documentation:** Swagger UI (FastAPI built-in) for API testing and visualization

---

🖥️ Deployment

- **Backend:** AWS Lightsail (FastAPI server deployed on Ubuntu instance)  
- **Production setup:** Gunicorn + Uvicorn  
- **Port:** 8000 opened for external API access  

```bash
📁 backend/
├── domain/
│   ├── user_router.py        # Defines API routes for user operations
│   └── user_schema.py        # Pydantic models for request/response validation
├── migrations/               # Alembic migration files
├── .gitignore                # Files to exclude from Git
├── alembic.ini               # Alembic configuration
├── database.py               # SQLite connection and session management
├── main.py                   # FastAPI entry point
├── models.py                 # SQLAlchemy models
├── security.py               # OAuth2 & JWT authentication logic
├── test.db                   # SQLite database file
├── test.sqbpro               # SQLite Browser project file
```

- **frontend:** javascript, Phasor3

```bash
📁 frontend/
├── assets/
│   ├── fonts
|   ├── images
|   ├── item            
│   └── startscene
├── assets/
│   ├── fonts
|   ├── images
|   ├── item            
│   └── startscene        
├── index.html                 # SQLite database file
├── netlify.tomi               # SQLite Browser project file
```
