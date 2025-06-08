# Smart-City-Wellbeing-System
A Figma Application done for the course INFO5100 - Application Engineering Development

# 🏙️ Smart City Well-being Analysis and Intervention System

A comprehensive urban health and safety monitoring system developed as part of the **INFO5100: Application Engineering & Development** course at **Northeastern University**. This project combines IoT, data analysis, AI, and system design (Figma) to build a smarter and healthier city ecosystem.

---

## 📌 Project Objective

Our system is designed to:

- 🩺 Enhance public health & safety through real-time monitoring  
- 🧘 Promote individual wellness with personalized dashboards  
- 🏘️ Foster community engagement via survey feedback  
- 📊 Drive data-informed decision-making for city planners  
- 🔄 Enable continuous improvement through automation and AI  

---

## 🖼️ UI/UX Highlights

We designed a fully interactive and citizen-friendly system interface with:

- 🔐 **Login Page** (Admin & User access)
- 📊 **Real-Time Dashboard** (Air quality, temperature, health score)
- 🧠 **Personal Wellness Module** (Integrated with IoT & wearables)
- 📝 **Survey Forms** (For gathering feedback & demographic data)
- 🚨 **Alerts Page** (Environmental and emergency notifications)

> 🖍️ Designed using Figma & hand sketches  
---

## 🏗️ System Architecture

The system is structured into the following layers:

1. **Application Layer**: Handles login, sessions, and API control  
2. **IoT & Sensor Layer**: Collects live environmental & health data  
3. **Data Storage & Processing**: MySQL + ML models for predictive analysis  
4. **Analytics Engine**: Detects patterns, raises alerts, forecasts needs  
5. **User Interface**: Web-based dashboards for Admins and Users

> 📂 See `/docs/system_architecture.png` for the full diagram

---

## 🧩 Domain Models & Database Schema

- 👤 `Users` ↔ `ResidentsHealthData` (One-to-One)  
- 👥 `Users` ↔ `UserActivityLog` (One-to-Many)  
- 🏥 `ResidentsHealthData` ↔ `HealthcareProviders` (Many-to-Many)  
- 🩺 `UserActivityLog` ↔ `ResidentsHealthData` (One-to-Many)

This schema supports detailed tracking of health, feedback, and engagement.

> 📂 See `/schema/db_schema.png` for full ER model

---

## 📈 Data Analysis & Predictive Insights

We explored key health equity indicators using:

- 📊 **Bar Chart** – Distribution of healthcare access  
- 🧠 **Pie Chart** – Physical health status insights  
- 💸 **Box Plot** – Income vs. healthcare access  
- 🧾 **Count Plot** – Income group access analysis  
- 🧍‍♂️ **Employment vs Mental Health** – Mental well-being patterns  
- 🤖 **Linear Regression** – Predicts need for new hospitals (33% accuracy)

> 📂 Visualizations available in `/analysis/`

---

## 🚨 Smart Features

| Feature                      | Description                                            |
|------------------------------|--------------------------------------------------------|
| 🌫️ Environmental Monitoring | PM2.5, CO2, Temp alerts using real-time sensors        |
| 🧬 Wellness Dashboard         | Tracks sleep, heart rate, step count                   |
| 📢 Alert Notifications       | Sends location-based warnings to users                |
| 📋 Survey & Sentiment        | Uses NLP on survey responses for public feedback       |
| 🧠 AI & ML Models            | Analyzes health gaps and predicts public needs         |

---

## 💡 Impact & Strategy

### 🌍 Potential Impact

- Improves quality of life and public safety  
- Empowers citizens with wellness insights  
- Reduces healthcare burden via preventive measures  
- Enhances engagement and trust through transparency  

### 🚀 Implementation Strategy

- 📡 IoT integration + anonymized data collection  
- 🔐 Strong privacy & access control measures  
- 👩‍🏫 Citizen onboarding via city campaigns  
- 🏥 Partner with public health agencies  
- 🧪 Run pilot tests → iterate based on feedback  
- 📦 Modular design for easy scalability  

---

## 🎥 Project Assets

| Type         | File Name                                   |
|--------------|----------------------------------------------|
| 📄 Design Doc| `Group08_SmartCityProject_SDD.pdf`           |
| 📽️ Video     | `Group08_SmartCityProject_Presentation.mp4`  |
| 🖼️ Slides     | `Group08_SmartCityProject_Slides.ppt`        |

---

## ✅ Course & Evaluation Info

This project was completed under the **INFO5100 – Application Engineering & Development** course. It meets the university’s evaluation criteria for:

- 🧠 AI & Data-Driven Innovation  
- 📐 System Design & Architecture  
- 🎨 UI/UX Wireframes  
- 📊 Analytical Modeling & Predictions  
- 🔒 Ethics & Privacy Considerations  
- 🌎 Real-World Impact Potential  

---

## 🙌 Team

- **Je Sai Kailash Pulipati**  
- **R. Deepthi**

📬 Connect with me on [LinkedIn](https://www.linkedin.com/in/je-pulipati/)
