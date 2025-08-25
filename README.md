# Health Screening: Lifestyle & Demographic Factors Affecting BP and CVD

**Subtitle:**  
*Heavier weight, older age, and obesity are strongly linked to higher blood pressure and increased risk of cardiovascular disease.*

---

## 📊 Data
- Dataset: anonymized health screening data  
- Cleaned file: `Health_Screening_Final.csv`  
- Rows after cleaning: ~[fill in number]  
- Columns: [fill in number]

---

## 🧹 Data Cleaning
- Fixed delimiter issues and standardized column types  
- Enforced valid ranges:
  - **Systolic BP:** 70–250 mmHg  
  - **Diastolic BP:** 40–150 mmHg  
- Removed **1,206 outliers (~1.7%)** (negative or extreme values)  
- Converted **AgeDays → Age (years)** and dropped redundant columns  
- Confirmed cleaning did not bias results (p-value > 0.05)  

---

## 🔑 Insights
- **Weight vs Blood Pressure:** Heavier people show higher systolic BP, especially those with cardiovascular disease.  
- **Age vs Blood Pressure:** BP increases with age, with older groups crossing the **130 mmHg hypertension threshold**.  
- **BMI Category vs Disease:** Obese and overweight groups have the **highest prevalence of cardiovascular disease**.  

---

## 📈 Dashboards (Tableau)
- Scatterplot: Weight vs BP (quadrants annotated)  
- Line chart: Age vs BP (threshold reference at 130 mmHg)  
- Stacked bar: BMI Category vs Cardiovascular Disease prevalence  

---

## 📜 License
MIT License
