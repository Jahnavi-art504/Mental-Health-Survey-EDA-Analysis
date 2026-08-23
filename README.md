# 🧠 Mental Health in Tech – EDA Project

This project presents a **comprehensive Exploratory Data Analysis (EDA)** of a mental health survey dataset, with a focus on **employees in the tech industry**. The primary aim is to uncover trends, treatment behaviors, and organizational support systems related to mental health, providing a data-driven foundation for crafting inclusive and effective workplace wellness strategies.

---

## 📌 Objective

To analyze employee responses on mental health in the workplace to:

* Understand treatment-seeking behavior and mental health interference.
* Explore how company size, benefits, and support systems influence well-being.
* Identify demographic and regional trends affecting mental health openness.
* Provide organizations with actionable insights to enhance mental health policies.

---

## 🧾 Dataset Overview

* **Total Records**: Varies based on survey cycle (example: \~1,200 responses).
* **Key Columns**:

  * `Age`, `Gender`, `Country`, `self_employed`, `work_interfere`
  * `family_history`, `treatment`, `benefits`, `care_options`, `wellness_program`
  * `seek_help`, `anonymity`, `leave`, `mental_health_consequence`, etc.

---

## 🧹 Data Cleaning & Preprocessing

* Standardized inconsistent entries (e.g., gender responses).
* Removed unrealistic age values (<18 or >80).
* Converted categorical responses into readable formats and encodings.
* Created derived columns (e.g., age groupings).
* Handled missing values and unified binary responses.

---

## 📊 Visual Analysis Summary

The dataset was explored through **15+ visualizations**, including:

### 🎂 Demographic Analysis

* **Age Distribution**: Most respondents are in their **late 20s to early 30s**.
* **Gender Composition**: Majority are **male**, with significantly lower treatment rates.

### 🌍 Regional Insights

* **Country-wise Responses**: Dominated by the **United States**, indicating participation bias.
* **Participation from non-Western countries is minimal**, suggesting global inclusivity gaps.

### 💼 Workplace Environment

* **Company Size**:

  * Majority work in **small to mid-sized firms (6–100 employees)**.
  * Indicates scalability challenges for implementing mental health programs.

* **Coworker & Supervisor Support**:

  * Positive correlation (**0.57**) between coworker and supervisor support.
  * Emphasizes the importance of leadership involvement.

* **Work Interference**:

  * Those reporting **frequent work interference** show higher likelihood of needing treatment.

### 🧾 Benefits & Wellness Programs

* **Treatment and Benefits**:

  * Around **50% are undergoing treatment**, suggesting growing openness.
  * Benefits, wellness programs, and care options are positively correlated with seeking help:

    * **Wellness Program ↔ Seek Help**: **0.47**
    * **Benefits ↔ Care Options**: **0.44**

* **Mental Health Leave Awareness**:

  * Many respondents **lack clarity on leave policies**, showing a need for transparent HR communication.

---

## 🔍 Key Insights

* High mental health interference among **young professionals in small companies**.
* **Male employees** are less likely to seek treatment, pointing to **gender-specific stigma**.
* **Coworker and supervisor support** are critical factors for positive mental health outcomes.
* **Wellness programs and benefits** directly influence openness to seeking help.
* Need for **greater awareness and communication** around **mental health leave**.
* **Regional bias** highlights a lack of global representation—suggesting the need for **more inclusive data collection**.

---

## 🛠️ Tools & Technologies Used

* **Python** (Jupyter Notebook)
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualization
* **Plotly** – Interactive plotting
* **LabelEncoder/OneHotEncoder** – Feature engineering

---

## 📌 Conclusion

This analysis provides a clear picture of mental health challenges within the tech industry. It highlights the importance of organizational policies, cultural factors, and individual openness. The findings equip companies to **design inclusive, gender-sensitive, and scalable mental health programs**, ultimately improving employee well-being and productivity.

---

## 📁 Project Structure

```
Mental-Health-in-Tech-EDA/
│
├── data/
│   └── mental_health_survey.csv
│
├── notebooks/
│   └── mental_health_eda.ipynb
│
├── images/
│   └── [Charts and Visuals]
│
├── README.md
└── requirements.txt
```
