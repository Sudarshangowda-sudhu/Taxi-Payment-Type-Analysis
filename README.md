# 🚖 **TAXI PAYMENT TYPE ANALYSIS**

## 🧠 **Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis**

---

## 🧩 **PROJECT OVERVIEW**

In the competitive taxi booking sector, maximizing revenue is essential for sustainability and driver satisfaction.  
This project investigates whether **payment methods (card vs. cash)** influence fare pricing and overall revenue generation using **Python data analysis**.

---

## 🎯 **OBJECTIVE**

To analyze the relationship between **total fare** and **payment method** using Python, statistical tests, and data visualization.  
The goal is to identify whether **card payments generate higher fares** than cash.

---
## 📊 **DATASET INFORMATION**

- **Source:** NYC Yellow Taxi Trip Data (January 2020)  
- **Key Columns:**  
  - `passenger_count`  
  - `trip_distance`  
  - `payment_type`  
  - `fare_amount`  
  - `trip_duration`

---

## ⚙️ **METHODOLOGY**

1. **Data Cleaning**  
   - Removed missing, duplicate, and invalid records.  
   - Filtered only essential variables.  
   - Retained valid payment types: **Credit Card (1)** and **Cash (2)**.

2. **Exploratory Data Analysis**  
   - Analyzed fare, distance, and passenger trends.  
   - Visualized payment distribution and mean fare comparison.

3. **Statistical Testing**  
   - Conducted **t-test** to check if card and cash fares differ significantly.

---

## 🔍 **KEY FINDINGS**

| Metric | Credit Card | Cash |
|--------|--------------|------|
| Mean Fare | 13.70 | 12.25 |
| Payment Share | 68% | 32% |
| Average Trip Distance | Higher | Lower |

- Card users tend to travel longer distances.  
- Majority (68%) of rides were paid by **credit card**.

---

## 🧮 **HYPOTHESIS TESTING**

- **Null Hypothesis (H₀):** No difference in average fare between card and cash payments.  
- **Alternative Hypothesis (H₁):** There is a significant difference.  

**Result:**  
T-statistic = 165.59, P-value = 0.0 → ✅ Reject H₀  

**Conclusion:** There is a significant difference between payment types.

---

## 💡 **BUSINESS INSIGHT**

Encouraging **credit card payments** can help drivers increase revenue,  
as such trips typically yield **higher fares and longer rides**.

---

## 🧰 **TOOLS & LIBRARIES USED**

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels  
- **Environment:** Jupyter Notebook  

---

## 📁 **PROJECT STRUCTURE**
Taxi_Payment_Type_Analysis/
- data/
  - yellow_tripdata_2020-01.csv
- notebooks/
  - Taxi_Payment_Type_Analysis.ipynb
- reports/
  - Taxi_Payment_Type_Analysis_Report.pdf
- README.md



👨‍💻 AUTHOR

Sudarshan Gowda
📍 Bengaluru, India
📧 sudarshan004.gowda@gmail.com
