# 📊 Batting Strategy Optimization using Data Analytics (Rohit Sharma)

## 📌 Overview

This project analyzes the batting performance of Rohit Sharma across **ODI, T20, and Test formats** using data analytics techniques.
The goal is to move beyond raw statistics and derive **actionable insights** that can inform strategic decision-making.

Instead of focusing only on descriptive analysis, this project emphasizes:

* Performance trade-offs (aggression vs consistency)
* Format-specific strategies
* Data-driven decision-making

---

## 🎯 Objective

* Transform raw cricket statistics into meaningful performance metrics
* Analyze how batting strategy varies across formats
* Identify **when aggressive vs stable play is most effective**
* Demonstrate how analytics can support decision-making

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Dataset

The analysis uses format-wise datasets:

* ODI.csv
* T20.csv
* TEST.csv

Each dataset contains yearly aggregated performance metrics such as:

* Runs, Balls, Outs
* Batting Average (Avg)
* Strike Rate (SR)
* Boundaries (4s, 6s)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Merged datasets across formats
* Handled missing values and ensured numeric consistency

### 2. Feature Engineering

Custom metrics were created to better evaluate performance:

* **Impact Score = Avg × Strike Rate**
* **Consistency Index = Runs / (Outs + 1)**
* **Boundary Percentage**

### 3. Exploratory Data Analysis

* Format-wise comparison of performance
* Trend analysis across years
* Aggression vs Consistency visualization

### 4. Correlation Analysis

* Examined relationships between runs, average, strike rate, and boundaries

---

## 📊 Key Insights

* **T20 format** shows the highest impact due to aggressive scoring (high strike rate)
* **Test format** demonstrates the highest consistency, indicating stable long-form performance
* **ODI format** provides a balanced combination of aggression and consistency
* Clear trade-off observed between **aggression (SR)** and **consistency (Avg)**

---

## 📈 Strategic Recommendations

* Use an **aggressive approach in T20** to maximize scoring impact
* Adopt an **anchor role in ODIs** for balanced performance
* Focus on **long innings and consistency in Tests**
* Avoid one-size-fits-all strategies; adapt based on format

---

## 🧠 Key Learnings

* Data analysis is not just about visualization, but about **deriving actionable insights**
* Proper metric design is critical for meaningful interpretation
* Context matters — insights must align with how data is generated

---

## 🚀 Future Improvements

* Add player comparison (benchmarking against other players)
* Perform statistical hypothesis testing
* Build an interactive dashboard (Tableau / Power BI)

---

## 📌 Conclusion

This project demonstrates how data analytics can be used to **translate raw performance data into strategic insights**.
While applied to cricket, the same analytical approach can be extended to **business decision-making scenarios**, such as customer segmentation, performance optimization, and strategy design.

---
