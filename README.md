# ACC102_Retail Profit Optimization: A Cost and Performance Analysis

## 1. Problem & User

This project is designed for retail managers and small business owners who aim to improve profitability. It addresses how to identify loss-making products and optimise cost structure using data analysis.

---

## 2. Data

* Dataset: Superstore Sales Dataset
* Source: Kaggle
* Access Date: 2026-04-15
* Key Fields: Sales, Profit, Quantity, Category, Sub-Category, Region, Order Date

The dataset reflects real-world retail operations and supports analysis of revenue, cost efficiency, and profitability patterns.

---

## 3. Methods

* Data loading and cleaning using pandas
* Feature engineering (Profit Margin and Month extraction)
* Groupby aggregation by product, region, and time
* Data visualisation using matplotlib
* Interpretation of results to generate business insights

---

## 4. Key Findings

* Several product sub-categories generate negative profit, indicating pricing or cost inefficiencies
* Profitability varies across regions, suggesting differences in operational performance
* Monthly trends show periods of stronger performance that can guide inventory and sales planning
* High sales do not necessarily lead to high profitability, highlighting the importance of profit margin analysis

---

## 5. How to run

### Step 1: Install required libraries

```bash
pip install -r requirements.txt
jupyter notebook
```

### Step 2: Prepare dataset

* Download the Superstore dataset
* Place `data.sample. superstore.csv` in the project folder

### Step 3: Run the notebook

```bash
jupyter notebook
```

Open `notebook.ipynb` and run all cells in order.

### Step 4: Workflow execution

* Load data using `pd.read_csv()`
* Perform cleaning using `info()` and `isnull()`
* Create new variables such as Profit Margin and Month
* Run groupby analysis for category, region, and time
* Generate charts and review insights

---

## 6. Product link / Demo

* notebook link: [http://localhost:8889/notebooks/notebook.ipynb](https://github.com/Kryptoniter246/ACC102-retail-profit-optimization-analysis/blob/main/notebook.ipynb)
* Demo Video:【ACC102 Track 2 Retail Profit Optimization: A Cost and Performance demo video】https://www.bilibili.com/video/BV1zXoKB8ERZ?vd_source=c8c9738cc881ceccaba5645084969be7

---

## 7. Limitations & next steps

* The dataset does not provide detailed cost components, limiting deeper cost structure analysis
* The analysis is descriptive and does not include predictive modelling

Future improvements:

* Introduce cost simulation and sensitivity analysis
* Incorporate external factors such as logistics or inflation data
* Develop an interactive dashboard for real-time analysis
