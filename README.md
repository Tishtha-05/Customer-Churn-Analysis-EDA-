# 📊 Customer Churn Analysis (EDA Project)

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a Customer Churn dataset to identify patterns and key factors that influence customer churn.

The objective is to:
- Understand customer behavior  
- Identify churn patterns  
- Discover key features affecting churn  
- Provide actionable business insights  

---

## 📂 Dataset Information

- Dataset Name: **Customer Churn Dataset**
- Total Records: **7043 rows**
- Total Features: **21 columns** :contentReference[oaicite:0]{index=0}  

### 🔑 Key Features:
- CustomerID  
- Gender  
- SeniorCitizen  
- Partner  
- Dependents  
- Tenure  
- PhoneService  
- InternetService  
- Contract  
- PaymentMethod  
- MonthlyCharges  
- TotalCharges  
- Churn  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## ⚙️ Data Preprocessing

- Converted `TotalCharges` from object to float  
- Replaced blank values with 0  
- Converted `SeniorCitizen` values (0/1 → Yes/No)  
- Checked for missing values (No null values found) :contentReference[oaicite:1]{index=1}  

---

## 📊 Exploratory Data Analysis

### 🔹 Churn Distribution
- Total churn rate: **26.54% customers churned** :contentReference[oaicite:2]{index=2}  
- Majority customers are retained (~73%)

---

### 🔹 Churn by Gender
- No major difference in churn between male and female customers  

---

### 🔹 Churn by Senior Citizens
- Senior citizens have a **higher churn percentage** compared to non-senior customers :contentReference[oaicite:3]{index=3}  

---

### 🔹 Churn by Tenure
- Customers with **low tenure (1–2 months)** churn more  
- Long-term customers tend to stay  

---

### 🔹 Churn by Contract Type
- **Month-to-month contract → Highest churn**
- **One-year & Two-year contracts → Lower churn** :contentReference[oaicite:4]{index=4}  

---

### 🔹 Churn by Services
- Customers without add-on services like:
  - Online Security  
  - Tech Support  
  - Device Protection  

  👉 have **higher churn rates** :contentReference[oaicite:5]{index=5}  

- Fiber optic users churn more compared to DSL users  

---

### 🔹 Churn by Payment Method
- Customers using **Electronic Check** have the highest churn probability :contentReference[oaicite:6]{index=6}  

---

## 📷 Visualizations

> ⚠️ Make sure your image names have **no spaces**

### 🔹 Churn Distribution
![Churn Distribution](./churn-distribution.png)

### 🔹 Churn by Gender
![Churn by Gender](./churn-gender.png)

### 🔹 Churn by Senior Citizen
![Churn by SeniorCitizen](./churn-senior.png)

### 🔹 Tenure Analysis
![Tenure Analysis](./tenure-analysis.png)

### 🔹 Contract Analysis
![Contract Analysis](./contract-analysis.png)

### 🔹 Services Analysis
![Services Analysis](./services-analysis.png)

### 🔹 Payment Method Analysis
![Payment Method](./payment-method.png)

---

## 💡 Key Insights

- 📉 26.54% customers have churned  
- 👴 Senior citizens churn more  
- ⏳ Short tenure customers are more likely to churn  
- 📃 Month-to-month contracts have highest churn  
- 🛡️ Add-on services reduce churn significantly  
- 💳 Electronic check users have higher churn  

---

## 🚀 Conclusion

Customer churn is strongly influenced by:
- Contract type  
- Tenure  
- Additional services  
- Payment method  

Businesses can reduce churn by:
- Promoting long-term contracts  
- Offering value-added services  
- Improving early customer experience  

---

## 📌 Future Work

- Build predictive churn model (ML)  
- Feature engineering  
- Customer segmentation  
- Deployment as dashboard  

---

## 👩‍💻 Author

**Tishtha Gandhi**  
B.Tech CSE (AI & ML)
