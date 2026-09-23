# E-Commerce Sales & Customer Analytics

## AICTE Data Analytics Internship Project

### Project Description

This project performs an end-to-end analysis of the Tableau **Sample -
Superstore** dataset. The analysis focuses on sales, profit, customers,
products, customer segments, regions, shipping performance, and
time-based trends.

The project uses Python with Pandas for data analysis and Plotly for
interactive visualizations.

### Objectives

-   Analyze sales and profit trends.
-   Compare categories and sub-categories.
-   Analyze regional and customer-segment performance.
-   Identify top customers and products.
-   Examine shipping performance.
-   Calculate business KPIs such as total sales, total profit, quantity,
    orders, customers, and profit margin.
-   Generate data-driven business insights.

### Dataset

The dataset used is Tableau's **Sample - Superstore / Superstore Sales**
sample dataset.

Official Tableau sample-data page:
https://public.tableau.com/app/resources/sample-data

Tableau describes Superstore as a sample dataset containing products,
sales, and profits for a fictitious company.

### Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   Plotly
-   CSV dataset

### Project Files

``` text
PiyushChawla_EcommerceSalesAnalytics.ipynb
requirements.txt
PiyushChawla_ProjectReport.docx
README.md
```

### Dataset File

Place the dataset file used by the notebook in the same directory as the
notebook:

``` text
Sample - Superstore.csv
```

The notebook currently loads it with:

``` python
pd.read_csv("Sample - Superstore.csv", encoding="latin-1")
```

### Setup Instructions

1.  Install Python 3.x.
2.  Open a terminal in the project folder.
3.  Install dependencies:

``` bash
pip install -r requirements.txt
```

4.  Place `Sample - Superstore.csv` in the project folder.
5.  Start Jupyter Notebook:

``` bash
jupyter notebook
```

6.  Open `PiyushChawla_EcommerceSalesAnalytics.ipynb`.
7.  Run the notebook cells from top to bottom.

### Analysis Included

-   Dataset overview and descriptive statistics
-   Data quality checks
-   Date conversion and date-based features
-   Monthly sales analysis
-   Sales by category and sub-category
-   Monthly profit analysis
-   Profit by category and sub-category
-   Sales and profit by customer segment
-   Sales-to-profit ratio
-   KPI summary
-   Regional analysis
-   Top customers
-   Top products
-   Shipping performance
-   Business insights

### Important Note

The Superstore data is a fictitious/sample business dataset intended for
analytics and training. It should not be presented as real company sales
data.

### Author

**Piyush Chawla**
