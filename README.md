# Loan Default Risk Analytics

This project provides a structured analysis approach using Excel, ensuring data-driven insights for financial risk management.

## Description

Imagine you're a data analyst at a finance company that specializes in lending various types of loans to urban customers. The company faces challenges in assessing customers with insufficient credit history, leading to potential defaults. Your task is to use **Exploratory Data Analysis (EDA)** to analyze patterns in the data and ensure that capable applicants are not rejected.

When a customer applies for a loan, the company faces two risks:
- If the applicant can repay the loan but is **not approved**, the company loses business.
- If the applicant **cannot repay the loan and is approved**, the company faces financial loss.

The dataset contains information about loan applications, with the following possible outcomes:
- **Approved**: The loan application was accepted.
- **Cancelled**: The customer withdrew the application during the approval process.
- **Refused**: The loan application was rejected.
- **Unused Offer**: The loan was approved, but the customer did not utilize it.

### Business Objectives:
The key objective of this project is to identify patterns that indicate whether a customer may have difficulty repaying their loan. These insights can help in:
- Denying loans to high-risk customers
- Reducing loan amounts for certain applicants
- Offering higher interest rates to risky applicants

By understanding the factors behind loan defaults, the company can make better data-driven decisions regarding loan approvals.

---

## Tech Stack

**Tool:** Microsoft Excel

---

## Data Analytics Tasks

### A) Identify Missing Data and Deal with it Appropriately
**Task:** Identify missing data in the dataset and decide on an appropriate method to handle it using Excel functions.

**Hint:** Use Excel functions such as `COUNT`, `ISBLANK`, and `IF` to detect missing data. Consider using `AVERAGE` or `MEDIAN` for imputation where applicable.

**Graph Suggestion:** Create a **bar chart** or **column chart** to visualize the proportion of missing values for each variable.

---

### B) Identify Outliers in the Dataset
**Task:** Detect and identify outliers in numerical variables using Excel statistical functions.

**Hint:** Use `QUARTILE` and `IQR` calculations, and apply **conditional formatting** to highlight outliers. Consider setting thresholds to determine valid or invalid data points.

**Graph Suggestion:** Use **box plots** or **scatter plots** to visualize the distribution and highlight outliers.

---

### C) Analyze Data Imbalance
**Task:** Determine if the dataset has a class imbalance problem and calculate its ratio.

**Hint:** Use `COUNTIF` and `SUM` functions to calculate class proportions. Compare class frequencies to assess data imbalance.

**Graph Suggestion:** Create a **pie chart** or **bar chart** to visualize the distribution of the target variable and highlight class imbalances.

---

### D) Perform Univariate, Segmented Univariate, and Bivariate Analysis
**Task:** Conduct univariate, segmented univariate, and bivariate analysis on consumer and loan attributes.

**Hint:**
- Use `COUNT`, `AVERAGE`, and `MEDIAN` for univariate analysis.
- Apply **filters, sorting, and pivot tables** for segmented univariate analysis.
- Use scatter plots and correlation calculations for bivariate analysis.

**Graph Suggestions:**
- **Histograms, bar charts, or box plots** for univariate analysis.
- **Stacked bar charts** to compare distributions in segmented analysis.
- **Scatter plots or heatmaps** to visualize relationships between variables and the target variable.

---

### E) Identify Top Correlations for Different Scenarios
**Task:** Segment the dataset based on different scenarios (e.g., clients with payment difficulties vs. others) and identify top correlations.

**Hint:** Use the `CORREL` function to calculate correlation coefficients within each segment and rank variables by their correlation strength.

**Graph Suggestion:** Create **correlation matrices or heatmaps** to visualize variable relationships. Highlight the most significant correlated variables using colors or shading.

---

## Insights on:
- Loan approval trends
- Common attributes of defaulting customers
- Key factors influencing loan repayment ability
- Data distribution patterns
- Outliers and their impact on decision-making

## More Information
This project is part of the **Trainity Data Analytics Course**. For more details on the project and other analytics insights, visit:
- [Trainity](https://trainity.in/data.html)
- [My Profile](https://trainity.space/recruitersProfile/public/66e52eb6fd616408e13b683f)

---

