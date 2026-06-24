# Uber Driver Allocation Optimization

## Overview
This project combines Data Science and Operations Research to improve driver allocation in a ride-hailing system. The goal is to predict ride demand and allocate drivers efficiently based on those predictions.

---

## Problem
Ride demand varies throughout the day, while the number of available drivers is limited. This creates a need to allocate drivers in a way that maximizes coverage and reduces inefficiency.

---

## Approach

### 1. Demand Prediction (Data Science)
- Built a simple Linear Regression model using hour as a predictor
- Built an improved Random Forest model using additional features such as pickup location
- Model comparison:
  - Simple Model: R² ≈ 0.44  
  - Improved Model: R² ≈ 0.91  

---

### 2. Driver Allocation (Operations Research)
- Total drivers available: 500  
- Each driver works 8 hours per day  
- Driver-hours are distributed proportionally based on predicted demand  

This ensures:
- More drivers during peak hours  
- Fewer drivers during low-demand periods  

---

## Results
- Improved demand prediction significantly enhanced allocation decisions  
- Driver allocation follows demand patterns  
- More efficient use of limited driver resources  

---

## Project Structure

