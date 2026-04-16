# 📊 Lung Cancer Risk Analysis & Predictive Insights Dashboard

## 🧩 Overview
This project analyzes the impact of smoking on lung cancer risk and symptom severity using Power BI and DAX, with the goal of identifying key risk drivers and supporting data-driven healthcare insights.

---

## 🎯 Objectives
- Identify key drivers of lung cancer  
- Analyze demographic risk patterns  
- Evaluate the impact of smoking  
- Detect high-risk individuals  

---

## 📊 Dataset
- Contains 3,000 patient records  
- Patient-level data including demographics, symptoms, and diagnosis  
- Includes co-risk amplifiers such as alcohol, anxiety, and chronic disease   

---

## 🧮 Key DAX

### Lung Cancer Rate
```DAX
Lung Cancer Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Data), Data[Lung Cancer] = 1),
    COUNTROWS(Data)
)
```

---
## 📈 Key Features
- Interactive dashboard with dynamic filtering  
- Risk-based conditional formatting  
- Two-level dashboard (Executive & Deep Dive)  
- Data modeling using unpivoted risk factors

---

## 📸 Dashboard Preview
![Overview](images/overview.png)  
![Deep Dive](images/deep-dive.png)

---

## 🔍 Key Insights
- Smoking shows measurable increase in lung cancer risk  
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
- Power BI  
- DAX (Data Analysis Expressions)  
- Power Query  
- Excel  

---

## 🚀 Conclusion
This project demonstrates the application of data modeling, DAX, and visualization techniques to generate actionable insights and support data-driven decision-making in healthcare.

---

## 👤 Author
Bright Twumasi  
Data Analyst | Power BI Developer  
Founder & Lead consultant, BrightData Consult
