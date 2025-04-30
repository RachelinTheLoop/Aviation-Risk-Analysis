# Aviation Accident Analysis Dashboard

## 📊 Overview
This project analyzes aviation accident data (1962–2023) from the National Transportation Safety Board. The goal is to help our company identify the **lowest-risk aircraft types** for entry into the aviation industry.

---

## 🧠 Business Understanding
Our company is expanding into commercial and private aviation. Stakeholders need to understand:
- Which aircraft makes/types are safest?
- What engine types are associated with more severe damage?
- How do accident trends vary by year and location?

---

## 📂 Data
**Source**: [NTSB Aviation Accident Database](https://www.ntsb.gov)  
**Format**: CSV  
**Columns used**:
- `MAKE`, `ENGINE_TYPE`, `AIRCRAFT_DAMAGE`, `LOCATION`, `TOTAL_FATAL_INJURIES`, `EVENT_DATE`, `ACCIDENT_NUMBER`, etc.

---

## 🔍 Analysis & Visualizations
Interactive visualizations were created using Tableau. The following key charts are included:

1. **Engine Type vs. Aircraft Damage**  
   _Insight_: Certain engine types are more prone to major damage.

2. **Aircraft Make vs. Location of Accidents**  
   _Insight_: Some makes dominate in high-accident regions.

3. **Aircraft Make vs. Total Fatal Injuries**  
   _Insight_: A few makes account for a large portion of fatalities.

4. **Year vs. Number of Accidents per Make**  
   _Insight_: Accident trends vary over time—some makes improve, others worsen.

**Link to Dashboard**: [Tableau Dashboard](<www.linkedin.com/in/rachelodhiambo>)

---

## ✅ Recommendations
1. **Prioritize aircraft with historically low fatality rates and damage severity**.
2. **Avoid aircraft makes with consistent high-risk records across years/locations**.
3. **Monitor accident trends yearly and update procurement strategy accordingly**.

---

## 📌 Conclusion
This project provides data-driven recommendations to help minimize safety risk as our company enters the aviation market.

---

## 💻 Files in this Repo
- `Projectphase1/JeffsAviation.ipynb`: Final Jupyter Notebook
- `Projectphase1/Aviation_clean.csv`: Cleaned dataset
- `Projectphase1/presentation.pdf`: Slide deck for stakeholders
- `dashboard/`: Tableau workbook 
- `.gitignore`: Git config file
## File Structure
Phase1project/
├── data/
│   └── Aviation_clean.csv
├── notebooks/
│   └── JeffsAviation.ipynb
├── outputs/
│   ├── Aviation_Dashboard.pdf
│   └── Presentation.pdf
├── README.md
└── requirements.txt

---

## 👤 Author
Rachel Odhiambo- Data Scientist
[LinkedIn Profile](www.linkedin.com/in/rachelodhiambo)

---

## ❓ Questions?
Feel free to reach out or submit issues in this repo!

