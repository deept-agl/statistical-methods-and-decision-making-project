# 📊 Statistical Methods & Decision Making (SMDM) Project

This project covers three major statistical case studies:  
1. **Wholesale Customer Spending Analysis**  
2. **Undergraduate Student Survey – Probability & Contingency Tables**  
3. **Hypothesis Testing on Shingle Moisture Content (One-sample & Two-sample T-tests)**  

Each problem applies descriptive statistics, probability theory, measures of variability, outlier detection, and inferential statistics.

---

# 🧩 Problem 1 — Wholesale Customer Analysis (Portugal Distributor)

Dataset: **440 retailers** × **9 variables** (Channel, Region, Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicatessen)

### 🔍 Tasks & Findings

#### **1. Exploratory Data Analysis**
- No missing values  
- Hotel channel & “Other” region record highest spending  
- All 6 items show **right-skewed distributions**  
- Delicatessen has **highest skewness**  
- Fresh is **least skewed**

#### **2. Behaviour Across Region & Channel**
- Spending patterns differ across items  
- Grocery & Frozen vary widely across regions  
- Delicatessen has low and stable spending everywhere  
- Fresh performs well across hotel and retail channels

#### **3. Variability (Coefficient of Variation)**
- **Most inconsistent:** Delicatessen (highest CV)  
- **Least inconsistent:** Fresh (lowest CV)

#### **4. Outlier Detection**
- Outliers present in **all six items**, especially in Grocery, Frozen & Delicatessen

#### **5. Business Recommendations**
- Stock more Fresh items (consistent demand)  
- Avoid overstocking Delicatessen  
- Retail channel drives strong sales for Milk, Grocery, Detergents_Paper  
- Hotel channel strong for Fresh & Frozen  
- Lisbon region has strong retail distribution opportunities

---

# 🧩 Problem 2 — CMSU Student Survey (Contingency Tables & Probability)

Dataset: **62 undergraduate students** × **14 survey attributes**

### 🔍 Tasks & Insights

#### **1. Contingency Tables**
Constructed for:
- Gender × Major  
- Gender × Graduation Intention  
- Gender × Employment  
- Gender × Computer Type  

#### **2. Probability Calculations**
- P(Male) = 46.8%  
- P(Female) = 53.2%  
- P(Male & intends to graduate) = 27.4%  
- P(Female & no laptop) = 6.5%  
- Conditional major probabilities for male & female students  
- GPA < 3 occurs for 27.4% of students  
- Earnings ≥ 50: 22.6% males, 29.0% females

#### **3. Normality Checks**
Variables: GPA, Salary, Spending, Text Messages  
- GPA follows normal distribution (Shapiro test accepted)  
- Salary, Spending, Text Messages do NOT follow normality

---

# 🧩 Problem 3 — Moisture Content in Shingles (Hypothesis Testing)

Dataset:  
- Shingles A: 36 observations  
- Shingles B: 31 observations  
Objective: Validate moisture content ≤ 0.35 pounds per 100 sq ft.

### 🔍 One-Sample T-Tests
- Shingles A mean = 0.317 → **within permissible limits**  
- Shingles B mean = 0.2735 → **within permissible limits**  
- Null hypothesis not rejected → moisture levels acceptable

### 🔍 Two-Sample T-Test
Hypothesis: μA = μB  
- p-value > 0.05  
- **Fail to reject null hypothesis** → moisture levels of A and B are statistically equal

---

# 🛠️ Tools & Techniques
- Python  
- Pandas, NumPy  
- SciPy (T-tests)  
- Matplotlib, Seaborn  
- Descriptive statistics, CV, outlier analysis  
- Probability & contingency tables  
- Normality tests (Shapiro-Wilk)


⭐ *If you found this project useful, please star the repository!*

