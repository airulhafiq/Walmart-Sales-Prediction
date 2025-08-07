# 🛒 Walmart Sales Prediction

A predictive analytics project to forecast **weekly Walmart sales**, understand key drivers of retail performance, and generate actionable insights for business stakeholders.

---

## 🔍 Project Description

This project explores historical Walmart sales data to build predictive models that estimate future weekly sales. It also provides business insights based on feature analysis, helping stakeholders make informed decisions on inventory, marketing, and store strategy.

---

## 📈 Key Insights & Strategic Recommendations

### 1️⃣ Impact of Holidays on Weekly Sales

**Insight**  
- Holiday weeks (`IsHoliday = True`) consistently show **higher sales** across nearly all departments and stores.  
- Notable spikes occur during **major events** like **Thanksgiving and Christmas**.

**Recommendation**  
- Plan **strategic promotions** and increase inventory levels for high-demand products during holiday weeks.  
- Introduce **holiday-themed discounts** and marketing to boost customer engagement.  
- Prioritize marketing in stores with historically higher holiday performance to maximize ROI.

---

### 2️⃣ Store Size & Regional Economic Conditions Affect Sales

**Insight**  
- Larger stores generally have **higher baseline sales**, but performance is affected by **CPI** and **unemployment rates**.  
- Stores in areas with **high unemployment or inflation** tend to underperform, regardless of size.

**Recommendation**  
- Design **location-specific strategies** based on local economic conditions.  
- Offer **budget-friendly products**, **smaller packages**, or **bulk discounts** in sensitive regions.  
- Adapt marketing language and promotions to match consumer purchasing power in each region.

---

### 3️⃣ Weather & Fuel Prices Affect Shopping Behavior

**Insight**  
- **Warm temperatures** increase sales of seasonal goods.  
- High **fuel prices** can lead to a **drop in foot traffic** and spending.

**Recommendation**  
- Promote **seasonal products** in warmer regions or during hotter months.  
- When fuel prices rise, consider offering **local promotions**, **free delivery**, or **fuel vouchers** to maintain sales momentum.

---

## 📂 Project Structure

```

Walmart-Sales-Prediction/
├── raw/ # Main dataset folder
│ ├── features.csv # Feature data (e.g., Fuel_Price, Temperature, Unemployment)
│ ├── stores.csv # Store types and size
│ ├── train.csv # Historical sales data (target)
│ └── test.csv # Data to predict
├── task.ipynb # Main Jupyter Notebook (model building & EDA)
├── finalprediction.csv # Final predictions on test set
├── requirements.txt # Python dependencies
└── README.md # Project overview (you’re here!)

````

---

## ⚙️ Tech Stack

- **Language**: Python 3.x
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Tools**: Jupyter Notebook, Git, GitHub

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/airulhafiq/Walmart-Sales-Prediction.git
cd Walmart-Sales-Prediction
````

2. **Install the dependencies**

```bash
pip install -r requirements.txt
```

3. **Launch the notebook**

```bash
jupyter notebook task.ipynb
```

## 📊 Modeling Summary

* Data cleaning & preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine learning models:

  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
* Model evaluation using RMSE, R²

---

## 👤 Author

**Airul Hafiq**
AI Engineer | Data Analyst | Python Enthusiast
📍 [LinkedIn](https://www.linkedin.com/in/airulhafiq/) | 🌟 [GitHub](https://github.com/airulhafiq)

---

💡 If you found this useful, give it a ⭐ and share with your network!


