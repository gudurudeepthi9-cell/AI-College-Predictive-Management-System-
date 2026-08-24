# AI College Predictive Management System

## 📌 Project Overview

AI College Predictive Management System is a machine learning-based web application designed to predict a student's academic risk based on academic performance and attendance data.

## 🎯 Objective

The main objective of this project is to identify students who may require additional academic support at an early stage.

## 🚀 Features

- Student academic risk prediction
- Attendance analysis
- Internal marks analysis
- Assignment performance analysis
- Previous CGPA analysis
- Machine learning-based prediction
- Simple web interface
- Prediction result dashboard

## 🧠 Machine Learning

The project uses the Random Forest Classification algorithm.

### Input Features

- Attendance Percentage
- Internal Marks
- Assignment Score
- Previous CGPA

### Output

The system predicts:

- Low Risk
- Medium Risk
- High Risk

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- HTML
- CSS
- Machine Learning

## 📂 Project Structure

                    AI COLLEGE PREDICTIVE
                    MANAGEMENT SYSTEM
                             │
          ┌──────────────────┼──────────────────┐
          │                  │                  │
       Student             Faculty            Admin
          │                  │                  │
          └──────────────────┼──────────────────┘
                             │
                       Flask Backend
                             │
                    ┌────────┴────────┐
                    │                 │
                 MySQL             ML Model
                    │                 │
                    └────────┬────────┘
                             │
                    Prediction Engine
                             │
              ┌──────────────┼──────────────┐
              │              │              │
           Low Risk      Medium Risk     High Risk
              │              │              │
              └──────────────┼──────────────┘
                             │
                     Analytics Dashboard
📸 Screenshots 
🏠 Screenshot 1 – Home / Prediction Page
📝 Student details input form
🤖 Screenshot 2 – AI Prediction Result
📊 Shows Low / Medium / High academic risk
🎓 Screenshot 3 – Student Dashboard
📈 Attendance, marks, CGPA and prediction history
👨‍🏫 Screenshot 4 – Faculty Dashboard
🔍 Student performance and at-risk students
👨‍💼 Screenshot 5 – Admin Dashboard
📊 Total students, departments and risk distribution
📈 Screenshot 6 – Analytics & Reports
📉 Performance charts and academic reports

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/AI-College-Predictive-Management-System.git
