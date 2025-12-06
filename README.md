# 🪔 Diwali Sales Analysis (Python Project)

A **Python-based data analysis project** that explores Diwali festival sales to uncover **customer behavior, purchasing patterns, high-performing states, occupations, and product categories**.
This analysis helps businesses make **data-driven decisions**, optimize festive campaigns, and identify the most profitable customer segments.

![Language](https://img.shields.io/badge/Language-Python-blue) ![Data](https://img.shields.io/badge/Data-CSV-green) ![Libraries](https://img.shields.io/badge/Libraries-Pandas%2FNumPy-yellow) ![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%2FSeaborn-orange) ![Skill](https://img.shields.io/badge/Skill-Data_Cleaning_&_Analysis-lightgreen) ![Focus](https://img.shields.io/badge/Focus-Diwali_Sales_Insights-red) ![Mode](https://img.shields.io/badge/Update-Historical_Data-purple)

---

## 🧩 Business Problem

Retail businesses experience a huge surge in demand during the **Diwali festival**, but most companies lack clarity on:

- Who their **most profitable customers** are  
- Which **age groups, genders, and marital statuses** buy the most  
- What **occupations and states** contribute maximum revenue  
- Which **product categories** generate the highest sales  
- How to design effective **marketing campaigns and inventory strategies**

Without these insights, businesses risk:

- Poor targeting  
- Inefficient discount strategies  
- Stock mismanagement  
- Missed revenue opportunities  

📌 **This project analyzes Diwali sales data to identify the most valuable customer segments and top-performing products, enabling better marketing and business decisions.**

---

# 📘 Reports Included

📄 **Business Problem Statement**  
➡️ `Problem_Statement.pdf`

📘 **Detailed Project Report (with charts & analysis)**  
➡️ `Diwali Sales Analysis Report.pdf`

---

# 📊 Project Overview

This project answers key business questions:

- 💰 Which **gender and age group** spends the most?  
- 🏙️ Which **states** and **occupations** drive the highest sales?  
- 🛍️ Which **product categories** are most popular?  
- 🎯 How do **marital status and demographics** influence purchasing behavior?  
- 📦 Which **products** perform best?

---

## 🧠 Key Insights

- 👩 **Women spend significantly more** than men during the Diwali season, making them the dominant customer segment.
  
- 🧾 The **26–35 age group** shows the highest purchase activity and total spending, especially among married women.

- 💍 **Married customers** contribute more to the overall revenue compared to unmarried customers.

- 🏙️ The top-performing states by sales are:
  - **Uttar Pradesh**
  - **Maharashtra**
  - **Karnataka**

- 👨‍💻 Customers working in **IT, Healthcare, and Aviation** professions drive the highest revenue.

- 🛒 **Clothing, Electronics, and Food** are the most purchased product categories, indicating strong demand during the festive season.

- 📦 The top-selling individual products (by order count) suggest a preference for **affordable, essential, and repeat-purchase items**.

- 🎯 Overall, the most valuable customer profile is:
  **Married women aged 26–35, working in IT or Healthcare, from top states like UP, Maharashtra, or Karnataka.**

---

# ⚙️ Tools & Technologies Used

| Tool / Technology | Purpose |
|------------------|---------|
| **Python (Pandas, NumPy)** | Data cleaning, manipulation, analysis |
| **Matplotlib & Seaborn** | Visualization and statistical plotting |
| **Jupyter Notebook** | Interactive analysis environment |
| **CSV Dataset** | Source data for analysis |
| **Business Analysis** | Insight generation & recommendations |

---

## 📂 Project Structure
```
Diwali_Sales_Analysis/
│
├── 📘 Diwali_Sales_Analysis.ipynb      # Main analysis notebook
├── 📄 Diwali_Sales_Data.csv            # Dataset file
│
├── 📄 Problem_Statement.pdf              # Business Problem
├── 📘 Diwali Sales Analysis Report.pdf   # Full Project Report
│
├── 🖼️ images/                          # Folder containing chart images
│ ├── male_female_by_age.png
│ ├── total_sales_by_occupation.png
│ └── marital_status_distribution.png
└── 📜 README.md                        # Project documentation
```

---

## 📸 Project Preview

Here are some sample visualizations from the analysis:

### 1️⃣ Male & Female by Age Group
This chart shows how **age and gender** affect purchase amounts, with women in the 26–35 age group contributing the most.

![Male & Female by Age Group](images/male_female_by_age.png)
&nbsp;

### 2️⃣ Total Sales by Occupation
This bar chart highlights how **different occupations** contribute to Diwali sales, with **IT, Healthcare, and Aviation** professionals being top spenders.

![Total Sales by Occupation](images/total_sales_by_occupation.png)
&nbsp;

### 3️⃣ Marital Status Distribution by Gender
This chart displays how **marital status influences spending behavior**, showing that **married women** lead in total purchase value.

![Marital Status Distribution by Gender](images/marital_status_distribution.png)
&nbsp;

---

## 📈 Visualizations

The notebook includes:

| Chart | Description | Graph Title |
|--------|-------------|--------------|
| Bar Plot | Total Amount by Gender | **Total Amount vs Gender** |
| Bar Plot | Total Amount by Age Group | **Total Amount vs Age Group** |
| Count Plot | Marital Status Distribution | **Marital Status Count** |
| Bar Plot | Total Amount by State | **Top States by Total Amount** |
| Bar Plot | Total Amount by Occupation | **Top Occupations by Total Amount** |
| Bar Plot | Total Amount by Product Category | **Top Product Categories** |
| Count Plot | Orders by Product Category | **Total Orders by Category** |

---

## 🪄 Step-by-Step Workflow

1. **Import Required Libraries**  
   Load essential Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn** for data handling and visualization.

2. **Load the Dataset**  
   Import the Diwali sales dataset (`Diwali_Sales_Data.csv`) into a Pandas DataFrame for analysis.

3. **Data Cleaning & Preprocessing**  
   - Remove unnecessary columns  
   - Handle missing values  
   - Fix incorrect or inconsistent entries  
   - Convert datatypes where needed  
   - Filter out invalid or incomplete records  

4. **Exploratory Data Analysis (EDA)**  
   Study customer demographics, sales trends, and behavioral patterns:
   - Gender-based purchasing  
   - Age group spending  
   - State-wise and occupation-wise performance  
   - Product category preferences  
   - Marital status impact  

5. **Data Visualization**  
   Use **Matplotlib** and **Seaborn** to create charts such as bar plots, count plots, and category-wise comparisons to uncover trends visually.

6. **Insights & Interpretation**  
   Evaluate patterns across demographics, states, occupations, and product categories to identify high-value customers and top-selling segments.

7. **Business Recommendations**  
   Provide actionable insights to help businesses improve marketing strategies, inventory planning, and festival-season sales optimization.

8. **Final Report Creation**  
   Compile all findings, charts, and insights into a structured **Project Report PDF** and **Business Problem Statement**.

---

## 🏁 Conclusion

The Diwali Sales Analysis reveals clear and actionable insights that businesses can leverage to improve their festive season performance:

- **Married women aged 26–35** emerge as the highest-value customer segment, contributing significantly to overall sales.  
- **Clothing, Electronics, and Food** stand out as the most popular product categories, indicating strong demand during the Diwali period.  
- Among all locations, **Uttar Pradesh, Maharashtra, and Karnataka** generate the highest sales, highlighting key target markets for festive promotions.  
- **IT, Healthcare, and Aviation** professionals show higher purchasing power, making them important customer groups for targeted marketing.  

Overall, the analysis provides a clear understanding of customer behavior, which can help retail businesses:

- Optimize their **marketing campaigns**  
- Plan **effective discount strategies**  
- Improve **inventory management**  
- Enhance **customer segmentation and targeting**

By using these insights, businesses can maximize their revenue and deliver personalized experiences during the Diwali festive season.

---

## 🚀 How to Run

1. Clone this repository  
```bash
git clone https://github.com/Harsh-Belekar/Diwali-Sales-Analysis-Python.git
cd Diwali-Sales-Analysis
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```
3. Open the notebook
```bash
jupyter notebook Diwali_Sales_Analysis.ipynb
```

---

## 🧩 Skills Demonstrated

- **Data Cleaning & Preprocessing**  
  Handling missing values, fixing incorrect entries, removing null data, and preparing the dataset for analysis.

- **Exploratory Data Analysis (EDA)**  
  Understanding trends, customer behavior, and patterns using descriptive statistics and visual exploration.

- **Data Visualization**  
  Creating meaningful and interactive plots using **Matplotlib** and **Seaborn** to highlight insights.

- **Python Programming**  
  Using Pandas, NumPy, and visualization libraries for analysis, transformation, and reporting.

- **Business Insights & Decision Making**  
  Translating raw data into actionable recommendations for marketing, sales strategy, and customer targeting.

- **Reporting & Documentation**  
  Creating a clear, structured project report and problem statement with professional charts and explanations.

- **Analytical Thinking**  
  Identifying high-value customer segments, key product categories, and revenue-driving factors.

---

## 🧑‍💻 Author

**👤 Harsh Belekar**  
📍 Data Analyst | Python | SQL | Power BI | Excel | Data Visualization  
📬 [LinkedIn](https://www.linkedin.com/in/harshbelekar) | 🔗[GitHub](https://github.com/Harsh-Belekar)

📧 [harshbelekar74@gmail.com](mailto:harshbelekar74@gmail.com)

---

## 📄 Dataset Disclaimer

The dataset used in this project is intended **solely for educational and analytical purposes**.  
It does not contain any sensitive personal information, and all customer details are anonymized.  
Any insights or interpretations derived from this analysis should not be considered as business advice for actual commercial use.

---

⭐ *If you found this project helpful, feel free to star the repo and connect with me for collaboration!*
