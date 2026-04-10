# lung-cancer-risk-analysis-dashboard
Lung Cancer Risk Analysis using Power BI and DAX
# 📊 Lung Cancer Risk Analysis Dashboard

### 🧩 Overview
This project analyzes lung cancer data to identify key risk factors and support early detection using an interactive Power BI dashboard.

---

### 🎯 Objectives
- Identify key drivers of lung cancer  
- Analyze demographic risk patterns  
- Evaluate the impact of smoking  
- Detect high-risk individuals  

---

### 📊 Dataset
Includes demographics, smoking behavior, symptoms, and lung cancer diagnosis outcomes.

---

### 🧮 Key DAX
```DAX
Lung Cancer Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Data), Data[Lung Cancer] = "Yes"),
    COUNTROWS(Data)
)
