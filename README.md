# 🌦️ Real Estate Ranking by Weather & Disasters

This project analyzes real estate data alongside weather and natural disaster variables to understand their impact on property value and safety. The goal is to **rank locations or properties based on environmental risks and climate conditions**, helping stakeholders make **data-driven investment or relocation decisions**.

---

## 📌 Project Objectives

- Integrate **weather and disaster data** with real estate information  
- Analyze how factors like **temperature**, **rainfall**, and **disaster frequency** affect property desirability  
- Rank or score regions based on **weather and safety metrics**  
- Provide **visual insights** into environment-driven property evaluation  

---

## 📊 Features and Workflow

### 🧹 Data Cleaning & Preparation

- Handling missing values  
- Renaming and reformatting columns for consistency  

### ☁️ Weather-based Analysis

- Average temperature, humidity, rainfall, etc.  
- Assigning **weather-based rankings** to locations  

### 🌪️ Disaster Risk Assessment

- Incorporating disaster frequency/severity data  
- Penalizing **high-risk areas** in the ranking logic  

### 🏠 Property Ranking Logic

- Combined score based on **weather and disaster impact**  
- Sorting and displaying **top and bottom-ranked areas**  

### 📊 Visualization

- **Bar plots** and **ranking tables** to present findings clearly  
- Comparative charts for risk distribution across regions  

---

## 📂 Dataset

The analysis is based on combined or simulated datasets, including:

- 🏘️ Real estate details (location, price, property type, etc.)  
- 🌤️ Weather metrics (temperature, humidity, rainfall)  
- 🌋 Natural disaster data (historical events per region)  

> *Note: The actual data was pre-merged or simulated for analysis. For production-ready applications, external APIs or government portals (like IMD or OpenWeatherMap) can be integrated for live updates.*

---

## 🛠 Tools & Technologies

- **Python**
- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualizations  
- **Jupyter Notebook** – Exploratory data analysis and logic implementation  

---

## 📈 Results & Insights

- Identified **regions with optimal weather** and **minimal disaster risk**  
- Built a reliable **ranking system** for real estate evaluation  
- Provided visual evidence supporting how **environmental conditions affect property attractiveness**  

---

## 📷 Sample Visualizations

> You can include actual image files (e.g., `.png`) inside an `images/` folder in your repo and reference them below.

### 📍 Top Ranked Locations Based on Weather and Safety
![Top Ranked Locations](images/top_ranked_locations.png)

### 🌪️ Risk Score Distribution by Region
![Risk Score Distribution](images/risk_score_distribution.png)

📌 *Save plots using* `plt.savefig("images/filename.png")` *and include them under* `images/` *directory.*

---
