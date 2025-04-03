### Markdown Report: Exploratory Data Analysis (EDA)

#### Sales Data Analysis & Trends

---

## 1⃣ Data Overview
This project analyzes a sales dataset to extract key insights using Exploratory Data Analysis (EDA), statistical moments, and interactive visualizations.

### Dataset Description
**Source**: Google Sheets

**Key Features:**
- **Item Visibility**: How often the item is displayed.
- **Sales**: Total revenue from an item.
- **Outlet Type**: The type of store (e.g., supermarket, grocery store).
- **Outlet Size**: Store size category (small, medium, large).
- **Item Fat Content**: Low Fat or Regular.
- **Outlet Establishment Year**: Year the store was established.

---

## 2⃣ Data Cleaning & Preprocessing
- **Dropped irrelevant columns**: `Item Identifier`, `Outlet Identifier`.
- **Fixed categorical inconsistencies**: Standardized `Item Fat Content`.
- **Handled missing values**:
  - `Item Weight` → Filled with **mean**.
  - `Item Visibility` → Filled with **median**.

---

## 3⃣ Statistical Moments Analysis
The following statistical measures were computed:

| Feature          | Mean  | Variance | Skewness | Kurtosis |
|-----------------|------:|---------:|---------:|---------:|
| **Item Visibility** | 0.07 | 0.00 | 1.17 | 1.68 |
| **Item Weight**  | 12.86 | 17.86 | 0.09 | -0.86 |
| **Sales**        | 140.99 | 3878.18 | 0.13 | -0.89 |
| **Rating**       | 3.97 | 0.37 | -2.19 | 8.01 |

### Insights:
- **Skewness > 1** → Indicates **highly skewed** data.
- **Kurtosis > 3** → Suggests **sharp peaks** (leptokurtic distribution).

---

## 4⃣ Interactive Visualizations & Insights

### Scatter Plot: Item Visibility vs Sales
🇼 **Observation**:
- Items with **higher visibility** do not necessarily have **higher sales**.
- Some **low-visibility** items still generate **high sales**.

**Business Insight**:
- **Marketing efforts** should focus on **high-selling low-visibility** items to maximize revenue.

---

### Bar Chart: Total Sales by Outlet Type
🇼 **Observation**:
- **Supermarkets** contribute the **highest total sales**.
- **Grocery stores** have significantly **lower sales**.

**Business Insight**:
- **Supermarkets** are the dominant retail channel; **expanding** their reach would increase profitability.

---

### Box Plot: Sales Distribution by Outlet Size
🇼 **Observation**:
- **Larger outlets** have a **higher median sales** value.
- **Small outlets** have a **wider sales variance**.

**Business Insight**:
- Investing in **medium and large** outlets leads to **consistent sales growth**.

---

### Correlation Heatmap
🇼 **Observation**:
- Sales have a **positive correlation** with **Item Weight** and **Outlet Size**.
- **Item Visibility** has a **weak correlation** with sales.

**Business Insight**:
- **Heavier items** tend to sell **more**, possibly indicating demand for **bulk purchases**.

---

### Pie Chart: Sales Contribution by Outlet Type
🇼 **Observation**:
- **Supermarkets** dominate more than **70%** of total sales.

**Business Insight**:
- Businesses should **diversify product distribution** in supermarkets.

---

### Line Chart: Sales Trend vs Outlet Age
🇼 **Observation**:
- **Older outlets** (established before **2000**) have **lower sales trends**.

**Business Insight**:
- Older outlets need **renovations, rebranding, or promotional strategies** to boost sales.

---

## 5⃣ Conclusion & Recommendations
- **Outlet Type & Size matter** → Supermarkets and large stores generate the **most revenue**.
- **Older outlets need investment** to boost performance.
- **Item Visibility doesn’t strongly affect sales**, meaning **pricing & promotions** play a bigger role.
