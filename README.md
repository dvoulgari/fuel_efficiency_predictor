# Fuel Efficiency Predictor - WeLEAD Final Project

## Introduction
This project is a **Proof of Concept (POC)** for a **business intelligence service** that predicts **vehicle fuel consumption (MPG)** using various car attributes.  
Developed for a **car rental consulting firm**, the predictive model assists in **fleet optimization and decision-making**.  
The model is built using the **Auto MPG dataset**.

---

## Dataset Overview
- **Dataset Name:** Auto MPG  
- **Number of Instances:** 398  
- **Number of Attributes:** 8  
- **Attribute Types:** Categorical, Real-valued  
- **Associated Task:** Regression  
- **Missing Values:** Yes  

**Key Attributes:**  
- MPG *(Target)* – Miles per gallon  
- Cylinders – Engine cylinder count  
- Displacement – Engine size (cubic inches)  
- Horsepower – Engine power *(with missing values)*  
- Weight – Vehicle weight (lbs)  
- Acceleration – 0–60 mph time (seconds)  
- Model Year – Two-digit encoded  
- Origin – Country of origin (categorical)  

---

## Usage

- `Project_WeLead_D01_.ipynb` – Runs D01 requirements  
- `Project_WeLead_D02_3.ipynb` – Runs D02 & D03 requirements  
- `Project_WeLead_D03.ipynb` – Separated code for D03 topic  
- `Project_WeLead_D02___.ipynb` – Additional separated code for submission  

---

## Requirements
- Python 3.x  
- pandas  
- NumPy  
- scikit-learn  
- matplotlib *(optional for visualization)*  

---

## Conclusion
This project demonstrates a **data-driven approach to predicting fuel efficiency**.  
It supports **car rental companies** in **fleet selection** and **fuel economy optimization**.  

**Future improvements:**  
- Integrate additional features  
- Improve prediction accuracy  
- Deploy as an API for real-time predictions  
