# Heart Disease Analysis | Python Pandas Project

Heart disease is the **leading cause of death worldwide**. It is strongly linked to risk factors such as **hypertension, diabetes, obesity, and unhealthy lifestyles**.  

This project performs **Exploratory Data Analysis (EDA)** on the **UCI Heart Disease Dataset** to uncover patterns and health indicators related to heart disease.  
**Note:** No machine learning models were built — this project focuses purely on **data cleaning, visualization, and statistical insights**.

---

## Dataset Overview

- **Source:** UCI Heart Disease Dataset (1988)  
- **Databases Included:** Cleveland, Hungary, Switzerland, Long Beach V  
- **Attributes:** 76 available, but analysis is performed on the most relevant **14 attributes**  
- **Target Variable:**  
  - `0` → No heart disease  
  - `1` → Heart disease present  

---

## Attribute Information

1. **age** → Patient’s age (in years)  
2. **sex** → Gender (1 = male, 0 = female)  
3. **chest pain type** (4 categories: typical angina, atypical angina, non-anginal, asymptomatic)  
4. **resting blood pressure** (in mm Hg)  
5. **serum cholestoral** (mg/dl)  
6. **fasting blood sugar > 120 mg/dl** (1 = true, 0 = false)  
7. **resting electrocardiographic results** (values 0, 1, 2)  
8. **maximum heart rate achieved**  
9. **exercise induced angina** (1 = yes, 0 = no)  
10. **oldpeak** → ST depression induced by exercise relative to rest  
11. **slope** → The slope of the peak exercise ST segment  
12. **number of major vessels (0–3)** → Detected via fluoroscopy  
13. **thal** → 0 = normal; 1 = fixed defect; 2 = reversible defect  
14. **target** → Presence of heart disease (0 = no disease, 1 = disease)  

**Note:** Patient identifiers (names, SSNs) were removed and replaced with dummy values.

---

## Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques:**  
  - Data Cleaning & Preprocessing  
  - Statistical Analysis  
  - Correlation Analysis  
  - Exploratory Data Visualization  

---

## Analysis Performed

1. **Data Cleaning**
   - Checked for missing/duplicate values  
   - Verified data types and corrected inconsistencies  

2. **Exploratory Data Analysis (EDA)**
   - Age & gender distribution  
   - Relationship between chest pain types and heart disease  
   - Cholesterol vs. heart disease analysis  
   - Resting blood pressure & maximum heart rate trends  
   - ST depression (oldpeak) and slope comparisons  
   - Multi-variable correlation heatmap  

3. **Insights**
   - Higher age and male patients show greater heart disease prevalence  
   - Chest pain type is strongly linked to diagnosis outcomes  
   - Cholesterol and resting BP showed moderate influence  
   - Maximum heart rate achieved is inversely related to disease presence  

---

## Visualizations

- **Histograms & Bar Charts** → Age, gender, chest pain distribution  
- **Boxplots** → Cholesterol, BP, max heart rate vs. target variable  
- **Correlation Heatmap** → Relationships among numerical features  
- **Pairplots** → Multi-feature trend exploration  

---

## License

- Dataset: **UCI Machine Learning Repository** (public domain for research/educational purposes)  
- Project: Released under the **MIT License**  

---

## Conclusion

This project demonstrates how **EDA (Exploratory Data Analysis)** can reveal key **risk factors of heart disease**.  
Findings highlight the importance of **age, gender, chest pain type, cholesterol levels, and maximum heart rate** as significant indicators.  

Such insights can help healthcare professionals in **early detection and preventive strategies**, even without advanced machine learning models.  
