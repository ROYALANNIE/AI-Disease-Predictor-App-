# 🏥 Symptom-Based Disease Predictor & Doctor Recommendation System

This project is a modern, interactive, and responsive web app that predicts possible diseases based on selected symptoms and recommends appropriate doctors with urgency levels. Built with **Streamlit**, it provides a user-friendly interface for quick medical guidance and educational health tips.

---

## 🎯 Project Description

This app allows users to:

- Select multiple symptoms from a dynamic list
- Predict the most likely disease using an intelligent model
- Get tailored doctor recommendations
- Understand the urgency of their symptoms
- Access basic health and emergency tips

> ⚠️ This tool is **not a substitute** for professional diagnosis. Always consult a certified medical practitioner.

---

## 📊 Dataset

We used a curated dataset consisting of symptoms and disease mappings. It includes:

- **Symptoms**: 131 unique symptoms
- **Diseases**: 41 disease classes
- **Source**: Multiple publicly available medical datasets from open-source platforms and cleaned for this project.
- The dataset was transformed using label encoding and used to train a classification model.

---

## 🎨 Features

✅ Modern responsive design with gradient backgrounds and animations  
✅ Interactive symptom selection with checkboxes and visual feedback  
✅ Real-time search to filter symptoms  
✅ Disease prediction with confidence scores  
✅ Doctor recommendations with urgency levels  
✅ Medical sidebar with emergency info and health tips  
✅ Mobile-friendly responsive layout  

---

## 🔧 How It Works

### 1. Symptom Selection
- Users can check symptoms or search for them in real-time.

### 2. Prediction Logic
- The app uses a machine learning model trained on symptom-disease mappings to predict the most likely disease based on selected symptoms.

### 3. Doctor Recommendation
- Each disease is mapped to relevant medical specialists.
- Urgency levels are displayed:
  - 🔴 Emergency
  - 🟠 High
  - 🟡 Medium
  - 🟢 Low

### 4. Additional Features
- Sidebar shows emergency contact info and rotating health tips.
- Smooth animations using `streamlit-animations`.

---



