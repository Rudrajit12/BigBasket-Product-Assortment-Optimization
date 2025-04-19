# Optimizing Product Assortment and Pricing Strategy for BigBasket

### **Project Category**: Exploratory Data Analysis  
### **Tools & Technologies**:  
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-43B02A?style=for-the-badge&logo=seaborn&logoColor=white)

**Other Tools**: NumPy, Jupyter Notebooks

## 🔍 Overview
BigBasket, India's leading online grocery platform, offers a vast range of products across multiple categories and brands. As the platform grows, maintaining an optimal product assortment, competitive pricing, and a diverse brand portfolio becomes increasingly important. This analysis of BigBasket’s product catalog (with over 28,000 products) identifies gaps, inefficiencies, and strategic opportunities for better assortment planning, pricing strategies, and brand positioning.

![BigBasket Image](https://drive.google.com/uc?export=view&id=1-OWtWGeZRBq2RAXzhZ8oxhQhef8qYTWE)

---

## Problem Statement
BigBasket, India’s leading online grocery platform, offers thousands of products spanning multiple categories, subcategories, and brands. However, with a rapidly expanding product catalog, the company faces challenges in maintaining an optimal product assortment, ensuring competitive pricing, and offering a diverse and appealing brand portfolio.

In the fiercely competitive landscape of online grocery retail, staying ahead requires more than just variety. It demands a strategic balance of product availability, price segmentation, and brand representation. Without consistent evaluation, the assortment risks becoming bloated, imbalanced, or misaligned with market demands—potentially leading to customer dissatisfaction and missed revenue opportunities.

This project undertakes a comprehensive analysis of BigBasket’s current product lineup to uncover insights that can drive smarter decision-making in assortment planning, pricing strategies, and brand positioning. Using a rich dataset of approximately 28,000 unique product entries, the analysis aims to identify gaps, inefficiencies, and strategic opportunities that can support data-driven growth initiatives.

This analysis is based on four core strategic pillars:

1. Product Assortment Optimization

2. Pricing Strategy Analysis

3. Brand and Category Positioning

4. Opportunity and Gap Identification

---

## 📂 Dataset Description
**[Download Dataset]()**

The dataset used in this analysis comprises 28,000+ products listed on BigBasket's platform. Each record represents a unique product offering and includes a variety of attributes related to product identity, categorization, pricing, and brand information.

### 🔍 **Key Features:**

- **Product Name** – The official title of the product listed on the platform.
- **Category & Subcategory** – Hierarchical classification of the product (e.g., Beverages → Juices).
- **Brand** – The brand under which the product is marketed.
- **Pack Size** – Describes the quantity or weight of the product (e.g., 1L, 500g).
- **MRP (Maximum Retail Price)** – The listed price before any discounts.
- **Selling Price** – The price after discounts or promotions.
- **Discount (%)** – The discount percentage applied, if any.
- **Rating** – Customer rating score (where available).
- **Number of Ratings** – The total number of user-submitted ratings.
- **Description/Tags** – Textual product descriptors (e.g., organic, sugar-free, etc.)

### 📦 **Structure:**

- **Format:** CSV (Comma Separated Values)
- **Rows:** ~28,000
- **Columns:** ~10–12 core attributes, depending on availability

This dataset provides a rich foundation for analyzing category depth, price strategies, brand presence, and identifying gaps in the product portfolio.

Before analysis, essential data preprocessing steps were applied:

1. Missing Values: Handled missing values in fields like product name, description, and ratings.

2. Redundant Columns: Removed unnecessary columns like the index.

3. Standardized Column Names: Ensured consistency by using lowercase and underscores for column names.

4. Optimized Data Types: Categorical columns were converted for better memory management.

5. Feature Engineering: Added features like Discount Amount and Discount Percentage.

6. Outlier Handling: Retained outliers in prices, which reflect high-end niche products.

---

## ⚖️ Objectives
This analysis is structured around four core strategic pillars:

1. ### **Product Assortment Optimization**
    - Evaluate product coverage across categories and subcategories.
    - Identify underrepresented or overrepresented segments.
    - Detect redundant or potentially outdated items.
2. ### **Pricing Strategy Analysis**
    - Examine price distributions and outliers within and across segments.
    - Analyze brand-wise price positioning and consistency.
3. ### **Brand and Category Positioning**
    - Assess brand dominance or fragmentation within each category.
    - Identify risks from low brand diversity or over-concentration.
    - Spot opportunities for private labels or third-party collaborations.
4. ### **Opportunity and Gap Identification**
    - Highlight high-performing but low-assortment categories.
    - Detect opportunities for tiered pricing strategies and product bundling.
    - Pinpoint gaps in offerings that could enhance customer value perception.

---

## ⚖️ Tools & Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔄 Key Steps Performed
- Data Loading and Initial Exploration
- Data Cleaning (handling missing values, duplicates, standardizing categories)
- Outlier Treatment (IQR method)
- Univariate, Bivariate & Multivariate Analysis
- Visualizations, Insights for four key Business Objectives
- Strategic Actions or Recommendations

---

## 📊 Key Insights & Recommendations
The analysis covered multiple areas using univariate, bivariate, and multivariate analysis techniques:

1. Univariate Analysis
Key Insight: Price distributions were heavily right-skewed, with most products priced under ₹500.

2. Bivariate & Multivariate Analysis
Key Insight: Certain brands positioned themselves with higher pricing across subcategories, and opportunities for tiered pricing strategies were identified.

3. Product Assortment Analysis
Key Insight: Some categories were overrepresented, leading to internal competition. Other subcategories lacked brand diversity, creating a monopoly risk.

4. Pricing Strategy Analysis
Key Insight: Some subcategories showed pricing inconsistencies, highlighting the need for better pricing governance.

5. Brand & Category Positioning
Key Insight: Certain emerging brands were highly rated but lacked visibility, indicating potential growth opportunities.

6. Gap & Opportunity Analysis
Key Insight: Opportunities for product bundling and premium product expansion in underrepresented subcategories were identified.

---

## 🛍️ Recommendations
Product Assortment Optimization
Action: Reduce redundancy in overrepresented subcategories, and expand product offerings in high-demand but underrepresented segments.

Pricing Strategy Enhancement
Action: Introduce tiered pricing to cater to budget, mid-range, and premium customers. Standardize pricing logic across categories.

Brand and Category Positioning
Action: Promote emerging high-rated brands and balance brand concentration in categories to mitigate supply risks.

Gap and Opportunity Identification
Action: Develop bundled offerings and expand into high-price, low-assortment subcategories.

---

## 💼 Project Status
✅ Completed - All stages of the EDA have been performed with actionable insights.

---

## 📅 Limitations & Future Improvements
### Limitations:
1. Lack of Sales Data: The dataset does not include actual sales figures, limiting performance correlation.

2. No Customer Demographics: Lack of customer data means insights are generalized rather than customer-specific.

3. Static Snapshot: The analysis is based on a one-time dataset, not considering time-dependent variations.

### Future Scope:
1. Transactional Sales Data: Incorporating actual sales data will enhance pricing and assortment strategies.

2. Customer Segmentation: Analyzing demographic and behavioral data will allow for more tailored recommendations.

3. Seasonal Trends: Time-series analysis will help understand demand fluctuations over time.

---

## Code Documentation
The analysis steps are conducted in Python Jupyter Notebooks. For running the analysis:

Install required libraries:
pip install pandas numpy matplotlib seaborn

Launch the notebook in Jupyter:
jupyter notebook

---

## Resources

- **IPYNB Notebook**: [Colab Link](https://colab.research.google.com/drive/1_yLgcjAHwjWokom_zBbConsCq27GFX53?usp=sharing)  
- **GitHub Repository**: [GitHub Link](https://github.com/Rudrajit12/BigBasket-Product-Assortment-Optimization) 

---

## References

1. [Kaggle - Books Sales and Ratings - EDA](https://www.kaggle.com/code/faresabbasai2022/books-sales-and-ratings-eda)
2. [Kaggle - Book Sales and Ratings](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)

---

## About the Author

**Author**: Rudrajit Bhattacharyya  

- **Email**: [rudrajitb24@gmail.com](mailto:rudrajitb24@gmail.com)  
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/rudrajitb/)  
- **GitHub**: [GitHub Profile](https://github.com/Rudrajit12)

---

