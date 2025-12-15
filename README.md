# health-ncd-analytics-dashboard
A healthcare analytics web application with login system and an interactive NCD screening dashboard built using HTML, Bootstrap, JavaScript, Chart.js, and PapaParse.
# 🏥 NCD Screening Dashboard – Health Department Case Study

A complete **web-based health management system** that integrates a hospital website with an **analytical Non-Communicable Disease (NCD) Screening Dashboard**.

This project was built as a **case study** to demonstrate frontend development, authentication, data analytics, and dashboard visualization skills.

---

## 🔍 Features

### ✅ Hospital Website
- Responsive Bootstrap-based UI
- Multiple sections (Home, Services, Departments, Contact)

### 🔐 Authentication System
- User Registration & Login
- Credentials stored in browser localStorage
- Authentication Guard to protect dashboard
- Secure Logout functionality

### 📊 NCD Screening Dashboard
- KPI Cards:
  - Total Screenings
  - Diabetes Positive Cases
  - Hypertension Positive Cases
  - Gender Distribution
  - Age Group Distribution
- Interactive Charts (Chart.js)
- PHC-wise summary table

### 📁 CSV Upload Support
- Load NCD screening data using **PapaParse**
- Real-time analytics from CSV file

---

## 🛠️ Technology Stack

| Component | Tools |
|---------|------|
| Frontend | HTML, CSS, Bootstrap 5 |
| Charts | Chart.js |
| CSV Processing | PapaParse.js |
| Authentication | JavaScript + localStorage |
| Development | VS Code, Live Server |

---

## ⚙️ How It Works

1. User registers using email & password
2. Login credentials are verified from localStorage
3. Dashboard access is allowed only after login
4. CSV file is parsed and analytics are generated
5. Logout clears the session

---

## 📂 Sample CSV Fields
- Patient ID  
- Gender  
- Age  
- PHC Name  
- Diabetes Result  
- Hypertension Result  
- Screening Date  

---

## 🚀 How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/ncd-screening-dashboard.git
