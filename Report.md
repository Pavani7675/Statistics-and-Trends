### Markdown Report for Exploratory Data Analysis (EDA)

####Analysis & Trends of Sales Data
---
##1⃣ Data Overview

This project is about analyzing the sales dataset to find some important key insights applying Exploratory Data analysis(EDA) and some interactive visualizations and also involves the use of statistical moments.

### Dataset Description

Source: Google Sheets

Key Features:

-Item Exposure: The frequency at which the item appears.

-Sales : Revenue generated from an item.

-Outlet Type: The type of store (e.g., supermarket, grocery store)

-Outlet Size: Small, Medium, Large.

-Item Fat Content: Regular; Low Additional Note

-Outlet Year of Incorporation: Year of establishment of the store.

---

##2⃣Data Cleaning & Preprocessing

-Flushed irrelevant columns: Item Identifier, Outlet Identifier.

-Repaired categorical errors: Standardized Item Fat Content.

-Handled missing values:

-`Item Weight`→ Mean filled.

-`Item Visibility`→ Median filled.
---
##3️⃣Moments Analysis

The following statistical parameters were calculated:

| Feature | Mean | Variance | Skewness | Kurtosis |

|-----------------|------:|---------:|---------:|---------:|

| Item Visibility | 0.07 | 0.00 | 1.17 | 1.68 |

| Item Weight | 12.86 | 17.86 | 0.09 | -0.86 |

| Sales | 140.99 | 3878.18 | 0.13 | -0.89 |

| Rating | 3.97 | 0.37 | -2.19 | 8.01 |

### Insights:

-Skewness > 1 → Signifies severely skewed data

-Kurtosis > 3 → Indicates pointed peaks (leptokurtic distribution).

##4⃣ Visualizations & Insights in Notebooks

### Scatter Plot: Visibility and Sales Scatter Plot

🇼 Observation:

-Just because something is more visible does not mean it sells better.

-High sales are still generated for some low-visibility items.

Business Insight:

-Low-visibility high-sales products should be marketed to maximize revenue.

###Sales by Types of Outlets — Bar Chart

🇼 Observation:

-Supermarkets lead the pack on overall sales.

-Grocery stores are down much, much less.

Business Insight:

-Supermarkets hold lucrative value in retail channels and scaling their access would lead to more profits.
---
### Box plot sales distribution by outlet size

🇼 Observation:

-Big outlets have higher median sales value.

-Small outlets sell more variably.

Business Insight:

-Sales are steady, investing from medium and large-sized outlets gives consistent growth in sales.
---

### Correlation Heatmap

🇼 Observation:

-The sales have positive correlation with Item Weight and Outlet Size.

-There is a weak correlation between Item Visibility and sales.

Business Insight:

-Heavier items are more often sold than smaller items, potentially suggesting a demand for bulk purchases.
---

### SALES CONTRIBUTION BY OUTLETS TYPE (Pie Chart)

🇼 Observation:

-Over 70% of total sales are dominated by supermarkets.

Business Insight:

-Product distribution in supermarkets should multi-channel.
---

### Line Chart Level: Sales Trend by Age of Outlet

🇼 Observation:

-Older media platforms (media established before 2000) are trending lower in sales.

Business Insight:

-You have older outlets that require refurbishing, rebranding, or promotions to drive movement.

---

##5⃣Conclusions & Recommendations

– Outlet Type & Size → Supermarkets/large stores contribute to higher revenue.

-Other older outlets require investment to increase performance

-Sales of Items Visibility doesn’t directly impact sales, hence pricing & promotions is more important.