# 📊 Aerofit Treadmill Customer Analysis

## 📌 Project Overview
This project analyzes the Aerofit treadmill dataset to understand customer purchasing behavior, product preferences, and usage patterns. The goal is to extract valuable insights that help Aerofit improve sales, marketing, and customer satisfaction.

---

## 🎯 Business Objectives
- Identify the key factors influencing treadmill purchases
- Understand customer segments based on demographics & fitness levels
- Analyze relationship between income, age, usage, and product preference
- Provide business-ready recommendations to increase sales

---

## 🏷️ Business Problem
Aerofit faces high competition, limited digital marketing, reduced demand post-pandemic, and lower sales of premium models. The company needs customer insights to tailor product offerings and targeting strategies.

---

## 📂 Dataset Details
| Feature | Description |
|--------|-------------|
| Product | Treadmill model (KP281, KP481, KP781) |
| Age | Customer age |
| Gender | Male / Female |
| Education | Years of education |
| MaritalStatus | Single/Partnered |
| Usage | Weekly usage frequency |
| Fitness | Self-rated fitness level |
| Income | Annual income |
| Miles | Miles run per week |

📌 Total Records: **180**  
📌 Format: **CSV / TXT**

---

## 🧹 Step 1: Data Cleaning
- Handled missing values (none found)
- Converted price format
- Detected and removed outliers in **Income** and **Miles** using IQR

---

## 📊 Step 2: Visual & Statistical Analysis

### 🔹 Univariate Analysis
- Histogram for Income and Miles
- Countplot for Product

### 🔹 Bivariate Analysis
- Scatter Plot: Income vs Miles
- Boxplot: Product vs Miles

### 🔹 Correlation Analysis
- Heatmap and Pairplot for numeric features

### 🔹 Customer Profiling
Users categorized into:
- **Budget & Beginners** (KP281 buyers)
- **Moderate Users** (KP481)
- **Premium & High-Fitness Users** (KP781)

---

## 🔍 Key Insights
✔ Young customers (18–30) are the highest buyers  
✔ Medium-income groups dominate purchases  
✔ High-fitness & high-income customers prefer KP781  
✔ Slight positive relationship between Income & Miles  
✔ KP281 is the most popular model overall  

---

## 💡 Business Recommendations
1. Promote KP781 to high-income and fitness-focused users  
2. Provide discounts/EMI plans for mid-income customers  
3. Improve after-sales support & maintenance service  
4. Launch app-based workout tracking for engagement  
5. Run targeted campaigns for youth on social media  
6. Create combo offers or subscription plans  

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook / Google Colab**

---

## 📝 Conclusion
This analysis helps Aerofit better understand its customer base and make data-driven decisions that boost product performance, customer engagement, and brand value in the market.

---
