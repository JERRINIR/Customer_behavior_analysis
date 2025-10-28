# Customer_behavior_analysis
# Customer Shopping Behavior Analysis README

## 📌 Overview

This project analyzes customer shopping behavior using a dataset of 3,900 transactions across multiple product categories. The objective is to uncover insights into customer demographics, purchasing trends, product preferences, discount impact, and subscription behavior. These insights help businesses optimize marketing strategies, improve customer retention, and increase overall revenue.

## 📂 Dataset Summary

* **Total Rows:** 3,900
* **Columns:** 18
* **Key Attributes Include:**

  * Customer Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item Purchased, Category, Purchase Amount (USD), Season, Size, Color
  * Behavioral Data: Previous Purchases, Frequency of Purchases, Review Rating, Discount Applied, Shipping Type
* **Missing Values:** 37 missing entries in the Review Rating column (handled through median imputation).

## 🛠 Tools & Technologies

| Tool                                   | Purpose                                          |
| -------------------------------------- | ------------------------------------------------ |
| **Python (Pandas, NumPy, Matplotlib)** | Data loading, cleaning, EDA, feature engineering |
| **MySQL**                              | Business analysis through SQL queries            |
| **Power BI**                           | Dashboard creation and visual storytelling       |
| **Gamma App**                          | Professional presentation generation             |
| **Jupyter Notebook**                   | Development and analysis environment             |

## 🔍 Project Workflow

### 1. **Data Preparation (Python)**

* Loaded the dataset using Pandas
* Renamed columns to snake_case
* Handled missing values in `review_rating` using median imputation per category
* Created new columns such as `age_group` and `purchase_frequency_days`
* Exported cleaned data to MySQL database

### 2. **SQL Analysis (MySQL)**

Key business questions answered:

* Revenue comparison by gender
* Top-rated and top-selling products
* Impact of discounts on spending behavior
* Subscription vs non-subscription spending trends
* Revenue contribution by age groups
* Customer segmentation based on purchase history

### 3. **Dashboard Development (Power BI)**

The dashboard includes:

* Total revenue and customer KPIs
* Category-wise and gender-wise sales trends
* Subscription insights
* Discount impact visualizations
* Interactive filters for age group, season, location

### 4. **Presentation (Gamma)**

* Created executive summary slides
* Added visual insights from Power BI
* Highlighted business recommendations

## 📊 Key Insights

* **Subscribers** spend significantly more than non-subscribers
* **Express shipping users** show higher purchase amounts
* **Clothing and Footwear** categories generate the most revenue
* **Age group 25-40** contributes the highest revenue
* **Discounts increase sales volume** but need optimization to protect profit margins

## ✅ Business Recommendations

* Promote subscription plans to retain loyal customers
* Introduce targeted campaigns for high-revenue age groups
* Highlight best-rated products in marketing
* Optimize discount strategies to increase profitability

## ▶ How to Run the Project

### **1. Clone the Repository**

```bash
git clone https://github.com/jerrinir/customer-shopping-analysis.git
cd customer-shopping-analysis
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run Python Notebook**

```bash
jupyter notebook analysis.ipynb
```

### **4. Load Data in MySQL**

* Import `customer_shopping_behavior.csv` into MySQL
* Use SQL scripts provided in the `sql_queries` folder

### **5. Open Dashboard in Power BI**

* Connect to MySQL database
* Refresh data to view insights

### **6. View PPT Presentation**

* Open `Customer_Shopping_Analysis.pptx` created using Gamma

## 📧 Contact

**Name:** Jerrin IR
**Email:** jerryjerry42503@gmail.com
**LinkedIn:** www.linkedin.com/in/jerrinir2003

---

🎯 *This project demonstrates strong analytical thinking, SQL knowledge, visualization expertise, and storytelling skills essential for data analyst roles.*

