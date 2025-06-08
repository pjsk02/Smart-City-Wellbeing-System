# Smart-City-Wellbeing-System
A Figma Application done for the course INFO5100 - Application Engineering Development

# 🏙️ Smart City Well-being Analysis and Intervention System

A comprehensive urban health and safety monitoring system developed as part of the **INFO5100: Application Engineering & Development** course at **Northeastern University**. This project combines IoT, data analysis, AI, and system design (using Figma) to build a smarter and healthier city ecosystem.

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

🖍️ Designed using Figma & hand sketches

> Login Page

![LoginPage](https://github.com/user-attachments/assets/6e4bdca1-3242-4fcc-abad-44c9fb48998e)

> Personal Wellness Dashboard

![Personal_Wellness_Dashboard](https://github.com/user-attachments/assets/c8390bb4-2bf1-4c40-9230-b44ed8e3951b)

> Environment Monitoring Dashboard

![Environmental_Monitoring_Dashboard](https://github.com/user-attachments/assets/c5880401-aad6-4585-83fe-4c14de87af4f)

> Alerts Dashboard

![Alerts_Dashboard](https://github.com/user-attachments/assets/a5d64aa1-a289-4f14-9cd2-d14dc57185d1)

> Survey Dashboard

![Survey_Dashboard](https://github.com/user-attachments/assets/97dc2186-ac4b-4012-8243-a30a524aa7bc)

---


## 🏗️ System Architecture

The system is structured into the following layers:

1. **Application Layer**: Handles login, sessions, and API control  
2. **IoT & Sensor Layer**: Collects live environmental & health data  
3. **Data Storage & Processing**: MySQL + ML models for predictive analysis  
4. **Analytics Engine**: Detects patterns, raises alerts, forecasts needs  
5. **User Interface**: Web-based dashboards for Admins and Users

![System_Architecture_Diagram](https://github.com/user-attachments/assets/8be7e7d5-3eaf-4849-bd2d-5f815e759574)

---

## 🧩 Domain Models & Database Schema

- 👤 `Users` ↔ `ResidentsHealthData` (One-to-One)  
- 👥 `Users` ↔ `UserActivityLog` (One-to-Many)  
- 🏥 `ResidentsHealthData` ↔ `HealthcareProviders` (Many-to-Many)  
- 🩺 `UserActivityLog` ↔ `ResidentsHealthData` (One-to-Many)

This schema supports detailed tracking of health, feedback, and engagement.

![Database_Schema](https://github.com/user-attachments/assets/12b0cbc3-7267-477b-b487-8b692e91ddd0)

---

## 📈 Data Analysis & Predictive Insights

We explored key health equity indicators using:

- 📊 **Bar Chart** – Distribution of healthcare access  
- 🧠 **Pie Chart** – Physical health status insights  
- 💸 **Box Plot** – Income vs. healthcare access  
- 🧾 **Count Plot** – Income group access analysis  
- 🧍‍♂️ **Employment vs Mental Health** – Mental well-being patterns  
- 🤖 **Linear Regression** – Predicts need for new hospitals (33% accuracy)

![Income_Distribution](https://github.com/user-attachments/assets/e318cc2c-d74e-401a-a2d1-7b5272857790)
![HealthCare_Levels](https://github.com/user-attachments/assets/cdf1604c-f41d-4986-b319-c3dae91e72a5)
![HealthCare_Distribution](https://github.com/user-attachments/assets/e099b45a-4ddc-434a-8f76-f53c0ab40361)
![PredictiveModel_LinearRegression](https://github.com/user-attachments/assets/a41cdba5-b99f-4a5a-ac03-e641b339bd1a)

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
- 🧪 Run pilot tests → iterate based on feedback  
- 📦 Modular design for easy scalability  

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
