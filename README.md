# Industry_EDA_Analysis

This project performs Exploratory Data Analysis (EDA) on an industry dataset containing information about companies across multiple industries, countries, and regions. The objective is to understand business performance patterns, identify trends, detect outliers, analyze relationships between variables, and derive actionable business insights.

The analysis covers univariate, bivariate, and multivariate techniques along with statistical interpretation of skewness and kurtosis.

## Dataset Features
The dataset contains the following business-related attributes:
- Industry
- Country
- Region
- Employee Count
- Annual Revenue (Million USD)
- Profit Margin (%)
- Customer Count
- Market Rating
- Founded Year
  
## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

# Project Workflow

## 1. Data Loading & Inspection

* Loaded dataset using **Pandas**
* Checked dataset dimensions
* Reviewed data types and structure
* Identified missing values
* Checked duplicate records

---

## 2. Data Quality Assessment

### Validation Performed

* Missing value analysis
* Duplicate record detection
* Invalid value verification
* Data consistency checks

### Findings

* No missing values detected
* No duplicate records found
* All numerical values were within valid business ranges
* Dataset is clean and analysis-ready

---

## 3. Univariate Analysis

### Variables Analyzed

* Employee Count
* Annual Revenue
* Profit Margin
* Customer Count
* Market Rating

### Key Findings

* Average employee count: **~2,607**
* Average annual revenue: **~$550 Million**
* Average profit margin: **~25%**
* Average customer count: **~50,449**
* Market ratings centered around **2.5/5**
* Most companies were founded between **1990–2019**

---

## 4. Categorical Analysis

### Categories Analyzed

* Industry Distribution
* Country Distribution
* Region Distribution

### Findings

* Balanced representation across industries
* Equal country representation
* North America accounts for approximately **50%** of records
* No significant class imbalance observed

---

## 5. Outlier Detection

### Methods Applied

* **Box Plot Analysis**

  * Visual inspection of outliers

* **IQR Method**

  * Interquartile Range-based detection

* **Z-Score Method**

  * Statistical outlier detection

### Findings

* Very few extreme observations detected
* No significant outlier treatment required
* Dataset remains well-balanced

---

## 6. Bivariate Analysis

### Employee Count vs Revenue

* Correlation ≈ **-0.002**
* No meaningful relationship observed

### Customer Count vs Revenue

* Correlation ≈ **-0.003**
* Revenue appears independent of customer volume

### Market Rating vs Revenue

* Correlation ≈ **0.015**
* No significant association observed

### Industry Revenue Comparison

* Retail companies generated the highest average revenue
* Healthcare companies generated the lowest average revenue

### Profit Margin by Industry

* Finance and Retail industries showed slightly higher profitability

### Revenue by Country

* USA recorded the highest average revenue
* Germany recorded the lowest average revenue

---

## 7. Correlation Analysis

### Analysis Performed

* Generated correlation heatmaps for numerical variables

### Findings

* Correlation coefficients were close to zero
* No strong positive or negative relationships detected
* Variables appear largely independent

---

## 8. Multivariate Analysis

### Variables Examined

* Revenue
* Employee Count
* Profit Margin
* Customer Count
* Industry
* Country
* Region
* Founded Year

### Key Insights

* Revenue remained relatively consistent across industries
* Employee count showed little impact on revenue generation
* Customer count did not significantly influence revenue
* Profit margins were stable across regions
* Company age had minimal effect on revenue

---

## 9. Statistical Distribution Analysis

### Skewness Analysis

#### Positive Skewness Observed In

* Employee Count
* Annual Revenue
* Customer Count

#### Interpretation

* Most companies operate at moderate levels
* A small number of large enterprises dominate these metrics

### Kurtosis Analysis

#### High Kurtosis Observed In

* Employee Count
* Annual Revenue

#### Interpretation

* Presence of extreme observations
* Large organizations significantly exceed average business size

---

# Business Insights

## High Revenue Industries

* Retail
* Finance
* Technology

## Most Profitable Industries

* Finance
* Retail

## Geographic Insights

* USA and India generated slightly higher revenues
* Revenue differences across countries were minimal

## Strategic Observations

* Revenue cannot be accurately predicted using a single variable
* Workforce growth alone does not guarantee increased revenue
* Operational efficiency and customer value creation are more important growth drivers

---

# Recommendations

## Growth Opportunities

Focus investments in:

* Retail Industry
* Finance Industry

## Resource Allocation

* Improve operational efficiency
* Optimize workforce productivity
* Enhance customer experience

## Market Expansion

* Similar performance across countries suggests opportunities for international expansion

## Competitive Strategy

Organizations should prioritize:

* Innovation
* Customer retention
* Operational excellence
* Sustainable growth strategies

---

# Key Conclusions

* Dataset is clean, balanced, and suitable for EDA
* No major data quality issues were identified
* Strong correlations between business variables were not observed
* Revenue performance is relatively uniform across industries and regions
* The notebook demonstrates a complete EDA workflow including:

  * Data cleaning
  * Data visualization
  * Statistical analysis
  * Business insight generation
