# 🚖 Uber Trip Analysis & Machine Learning Project

## 📌 **Project Overview**
### **This project focuses on analyzing Uber trip data to uncover peak demand patterns and implementing a Random Forest Regressor model. The goal is to accurately predict future trip volumes to assist in better vehicle allocation and resource management.**

## 📊 Dashboard Preview
![Uber Dashboard Demo](Uber%20demo.gif)
---

## 🛠️ **Tech Stack**
* **Programming:** `Python 3.x`
* **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`
* **Machine Learning:** `Random Forest Regression`
* **Visualization:** `Power BI Desktop`, `Seaborn`, `Matplotlib`

---

## 📊 **Key Results & Insights**

### 📈 **Model Performance**
* **Algorithm:** Random Forest Regressor
* **Accuracy (R² Score):** **0.98**
* **Predictive Power:** The model successfully captures daily fluctuations and demand spikes.

### 💡 **Business Insights**
* **Weekly Trends:** Identified that **weekends (Friday-Sunday)** experience a 30% surge in trip volume compared to weekdays.
* **Base Performance:** Dispatching Base **B02764** was identified as the highest-performing hub with the most active vehicles.
* **Demand Forecasting:** Predicted trip values align closely with actual data, allowing for proactive driver scheduling.

---

## 🚀 **Project Structure & Files**



| File Name | Description |
| :--- | :--- |
| **`notebook.ipynb`** | Full Python source code (Cleaning, EDA, and ML Model). |
| **`Uber trip analysis dashboard.pbix`** | Interactive Power BI Dashboard file. |
| **`Uber.csv`** | The raw input dataset. |
| **`Uber_Analysis_Final.csv`** | Processed data with ML predictions for Power BI. |

---

## 💻 **How to Run the Project**

### **1. Python Analysis**
Run the `notebook.ipynb` notebook in VS Code or Jupyter. Ensure you have the following installed:
`pip install pandas scikit-learn matplotlib seaborn`

### **2. Power BI Dashboard**
1. Open `Uber trip analysis dashboard.pbix` using **Power BI Desktop**.
2. If the data doesn't load, go to **Transform Data** and update the source path to point to `Uber_Analysis_Final.csv` on your computer.

