
#  Car Market Trends Analysis

An exploratory data analysis project focused on understanding **used-car pricing, depreciation, vehicle age, usage patterns, and market trends** using Python and interactive visualizations.

> **Minor Project — Internship | Data Analytics**

---

##  Project Overview

The **Car Market Trends Analysis** project analyzes a used-car dataset to identify the major factors influencing vehicle selling prices and depreciation.

The analysis covers vehicle characteristics such as **present price, selling price, car age, kilometers driven, fuel type, seller type, transmission, and previous ownership**.

The project follows a complete data analytics workflow, from data cleaning and feature engineering to exploratory analysis, business insights, recommendations, and an interactive dashboard.

---

##  Objectives

* Analyze factors affecting used-car selling prices.
* Understand the relationship between **present price and selling price**.
* Study the impact of **car age and kilometers driven** on resale value.
* Analyze price differences across **fuel types, seller types, transmission types, and ownership levels**.
* Measure vehicle depreciation.
* Identify high-value and frequently occurring car models.
* Generate actionable business insights for buyers and sellers.
* Build an interactive dashboard for summarizing key findings.

---

##  Dataset

The dataset contains information about used cars and their market values.

### Dataset Features

| Column          | Description                          |
| --------------- | ------------------------------------ |
| `Car_Name`      | Name/model of the car                |
| `Year`          | Manufacturing year                   |
| `Selling_Price` | Price at which the car is sold       |
| `Present_Price` | Current/ex-showroom price of the car |
| `Kms_Driven`    | Kilometers driven                    |
| `Fuel_Type`     | Fuel type of the vehicle             |
| `Seller_Type`   | Dealer or individual seller          |
| `Transmission`  | Manual or automatic                  |
| `Owner`         | Number of previous owners            |

---

##  Technologies & Tools

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Plotly** — Interactive visualizations
* **Google Colab** — Development environment
* **GitHub** — Project version control and documentation

---

##  Project Workflow

```text
Dataset
   ↓
Data Loading & Inspection
   ↓
Data Cleaning
   ↓
Missing Value & Duplicate Check
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Price & Depreciation Analysis
   ↓
Multivariate Analysis
   ↓
Model & Market Analysis
   ↓
KPI Summary
   ↓
Business Insights
   ↓
Recommendations
   ↓
Interactive Dashboard
```

---

##  Data Cleaning

The following data preparation steps were performed:

* Inspected dataset structure and data types.
* Checked for missing values.
* Checked for duplicate records.
* Removed duplicate records where required.
* Standardized column names.
* Validated categorical variables.
* Generated descriptive statistics for numerical features.

After cleaning, the final dataset contained **299 records**.

---

##  Feature Engineering

Additional analytical features were created to improve the analysis:

### Car Age

```text
Car Age = Current Year − Manufacturing Year
```

### Price Difference

```text
Price Difference = Present Price − Selling Price
```

### Depreciation Percentage

```text
Depreciation % =
((Present Price − Selling Price) / Present Price) × 100
```

Additional derived analysis includes **kilometers per year** and **car-age groups**.

---

##  Exploratory Data Analysis

The project includes both **univariate, bivariate, and multivariate analysis**.

### Univariate Analysis

* Selling price distribution
* Car age distribution
* Fuel type distribution
* Seller type distribution
* Transmission distribution
* Ownership distribution
* Numerical variable outlier analysis

### Bivariate Analysis

* Present Price vs Selling Price
* Car Age vs Selling Price
* KMs Driven vs Selling Price
* Selling Price by Fuel Type
* Selling Price by Seller Type
* Selling Price by Transmission
* Selling Price by Previous Owners
* Depreciation by Fuel Type
* Depreciation by Transmission
* Depreciation by Previous Owners

### Multivariate Analysis

* Car Age + Fuel Type + Selling Price
* Car Age + KMs Driven + Selling Price
* Fuel Type × Transmission
* Ownership × Depreciation
* Model-wise pricing analysis

---

##  Advanced Analysis

The project also includes:

* Correlation analysis
* Correlation ranking with selling price
* Average selling price by different categories
* Average depreciation analysis
* Top 10 cars by selling price
* Top 10 cars by present price
* Top 10 cars with highest depreciation
* Most common car models
* Model-wise performance analysis
* Outlier analysis
* Age-group based analysis
* KMs-per-year analysis

---

##  Key Performance Indicators (KPIs)

The dashboard summarizes important business KPIs including:

* **Total Cars**
* **Average Selling Price**
* **Average Present Price**
* **Average Car Age**
* **Average Kilometers Driven**
* **Average Depreciation**
* Highest Selling Price
* Lowest Selling Price

---

##  Key Business Insights

The analysis highlights several important patterns in the used-car market:

1. **Present Price is strongly associated with Selling Price**, making it one of the most important pricing variables.

2. **Car age has a significant relationship with resale value**, with older vehicles generally commanding lower selling prices.

3. **Selling prices are concentrated in lower-price segments**, while a smaller number of premium vehicles create a long right tail in the distribution.

4. **Kilometers driven provides an important indicator of vehicle usage** and is associated with resale value.

5. **Fuel type, transmission, seller type, and ownership history** create differences in pricing and depreciation patterns.

6. **Ownership history influences resale value**, with vehicles having fewer previous owners generally being more attractive in the resale market.

7. **Depreciation varies across different vehicle categories**, demonstrating that resale value is influenced by multiple factors rather than car age alone.

> **Note:** Insights are based on patterns observed in the analyzed dataset and should not be generalized to the entire used-car market without additional data.

---

## Business Recommendations

### For Sellers & Dealers

* Consider vehicle age and present market value when setting resale prices.
* Highlight low kilometer usage and lower ownership history in listings.
* Use historical depreciation patterns to establish realistic asking prices.
* Segment vehicles based on fuel type, transmission, age, and usage.

### For Buyers

* Compare selling price with the vehicle's present price before purchasing.
* Consider car age and kilometers driven together rather than independently.
* Check ownership history before making a purchase decision.
* Compare similar models to identify better-value vehicles.

### For Automotive Platforms

* Develop data-driven pricing recommendations.
* Build depreciation estimation tools.
* Use vehicle characteristics to create personalized recommendations.
* Monitor pricing trends across different vehicle segments.

---

##  Interactive Dashboard

An interactive **Car Market Trends Dashboard** was developed using Plotly.

The dashboard provides a consolidated view of:

* Key Performance Indicators
* Selling Price Distribution
* Present Price vs Selling Price
* Average Selling Price by Fuel Type
* Car Age vs Selling Price
* KMs Driven vs Selling Price
* Average Depreciation by Previous Owners

The dashboard helps users quickly understand major pricing and depreciation patterns without going through the complete analysis notebook.

---

## 🚀 Future Scope

The project can be further extended by:

* Developing a **used-car selling price prediction model**.
* Applying machine learning algorithms such as Linear Regression, Random Forest, and Gradient Boosting.
* Creating an automated car-price recommendation system.
* Adding more real-world vehicle and market data.
* Developing a web-based pricing application.
* Implementing model explainability to understand pricing predictions.

---

## 👩‍💻 Author

**Riya**

**BCA | Data Analytics & Business Analytics**

---

## ⭐ Project Highlights

```text
✔ Data Cleaning
✔ Feature Engineering
✔ Exploratory Data Analysis
✔ Statistical & Correlation Analysis
✔ Price Analysis
✔ Depreciation Analysis
✔ Multivariate Analysis
✔ Business Insights
✔ Business Recommendations
✔ KPI Analysis
✔ Interactive Dashboard
```

---

