# Experiment 2 – Implementation of Data Visualization Techniques

## Aim
To analyze ecommerce transaction data and implement various data visualization techniques in R to extract meaningful insights and detect patterns.

---

## Objective
- To explore and preprocess ecommerce transaction data.
- To identify and visualize the distribution of transaction amounts.
- To detect outliers using boxplots.
- To analyze monthly sales trends through heatmaps.
- To enhance data interpretation using different types of visualizations.

---

## Dataset Description
**File:** `2.ecommerce_transactions.csv`

The dataset includes the following attributes:
- `Transaction_ID` – Unique identifier for each transaction
- `Transaction_Amount` – Monetary value of the transaction
- `Transaction_Date` – Date when the transaction occurred

---

## Methodology
1. Load the ecommerce transactions dataset into R.
2. Visualize the distribution of transaction amounts using histograms.
3. Detect and extract outliers with boxplots.
4. Convert transaction dates to proper date format.
5. Aggregate monthly sales and visualize them using a heatmap.
6. Use `ggplot2`, `dplyr`, and `tidyr` libraries for data manipulation and visualization.

---

## Visualizations Implemented

### Histogram of Transaction Amounts
- Displays the frequency distribution of transaction values.
- Helps identify common transaction ranges and data skewness.

Output File:  
- `Histogram of Transaction Amounts.png`

---

### Boxplot to Detect Outliers
- Highlights outliers in transaction amounts.
- Assists in understanding the spread and anomalies in data.

Output File:  
- `Boxplot of Transaction Amounts.png`

---

### Monthly Sales Heatmap
- Aggregates total sales per month.
- Uses color gradients to visualize monthly sales intensity.
- Facilitates easy detection of peak and low sales periods.

Output File:  
- `Monthly Sales Heatmap.png`

---

## Tools & Libraries Used
- R (version 4.4.1)
- ggplot2
- dplyr
- tidyr
- RStudio

---

## Conclusion
Data visualization is crucial for understanding complex datasets and making data-driven decisions.  
This experiment demonstrates practical use of R’s visualization libraries to analyze ecommerce data comprehensively.

