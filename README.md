# 📊 Lung Cancer Risk Analysis Dashboard

## 🧩 Overview
This project analyzes the impact of smoking on lung cancer risk and symptom severity using Power BI and DAX.

---

## 🎯 Objectives
- Identify key drivers of lung cancer  
- Analyze demographic risk patterns  
- Evaluate the impact of smoking  
- Detect high-risk individuals  

---

## 📊 Dataset
- Patient-level data including demographics, symptoms, and diagnosis  
- Includes co-risk amplifiers such as alcohol, anxiety, and peer pressure  

---

## 🧮 Key DAX
```DAX
Lung Cancer Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Data), Data[Lung Cancer] = "Yes"),
    COUNTROWS(Data)
)

---

## 📸 Dashboard Preview
![Overview](images/overview.png)  
![Deep Dive](images/deep-dive.png)

---

## 🔍 Key Insights
- Smoking is associated with increased lung cancer risk  
- Certain demographics show higher prevalence  
- Key symptoms strongly correlate with diagnosis  
- Co-risk factors amplify overall risk

---

## 💡 Recommendations
- Target smokers for early screening  
- Focus on high-risk symptoms  
- Increase awareness programs

---

## 🧰 Tools Used

Power BI | DAX | Power Query | Excel
