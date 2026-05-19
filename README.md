# Superstore Sales Analysis Using SQL and Python

## Project Overview
This project analyzes Superstore retail sales data using SQL and Python to uncover insights related to revenue performance, profitability, customer behavior, discount strategies, and regional trends.

The project combines SQL for data extraction and aggregation with Python for data cleaning, exploratory data analysis (EDA), and visualization.

---

## Business Problem
Retail businesses generate large volumes of transactional data, but raw data alone does not provide actionable insights. This project aims to identify key business drivers, evaluate sales performance, and generate recommendations to improve profitability and operational efficiency.

---

## Project Objectives
- Analyze sales and profit performance across categories and regions
- Identify top-performing customers
- Examine the relationship between discounts and profitability
- Discover monthly sales trends
- Explore correlations between business variables
- Generate actionable business recommendations

---

## Dataset Description
The dataset contains retail transactional records including:

- Order Date
- Customer Name
- Product Name
- Category
- Region
- Sales
- Profit
- Discount
- Quantity

---

## Technologies Used

### Programming Languages
- Python
- SQL (MySQL)

### Python Libraries
- pandas
- numpy
- matplotlib
- seaborn
- sqlalchemy
- pymysql

### Tools
- VS Code
- Jupyter Notebook
- MySQL Workbench

---

## Exploratory Data Analysis (EDA)
EDA was performed to:
- analyze sales and profit distributions
- identify outliers
- explore correlations between variables
- discover sales trends and business patterns

Visualizations used:
- Histogram
- Boxplot
- Heatmap
- Bar Chart
- Line Chart
- Scatter Plot

---

## Business Questions

### 1. Which product categories generate the highest revenue?
Analyzed category-level sales performance to identify the strongest revenue-generating categories.

### 2. How do sales change over time?
Examined monthly revenue trends to identify seasonality and purchasing behavior.

### 3. Which regions are the most profitable?
Compared regional profit performance to evaluate operational effectiveness.

### 4. How do discounts impact profitability?
Investigated the relationship between discount levels and profit.

### 5. Who are the top customers by revenue?
Identified high-value customers contributing the largest share of total revenue.

---

## Key Findings
- Technology generated the highest overall revenue.
- Sales showed noticeable seasonal peaks during year-end periods.
- Higher discount levels were associated with lower profitability.
- A small group of customers contributed significantly to total revenue.
- The West region generated the highest overall profit.

---

## Business Recommendations
- Reduce excessive discounting to improve profit margins.
- Focus retention strategies on high-value customers.
- Increase investment in high-performing product categories.
- Investigate lower-performing regions for operational inefficiencies.
- Use seasonal trends to optimize marketing campaigns.

---

## Project Structure

```text
superstore-sales-analysis/
│
├── notebooks/
│   └── Superstore_Sales_Analysis.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/superstore-sales-analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd superstore-sales-analysis
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql notebook
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

Open:

```text
Superstore_Sales_Analysis.ipynb
```

and run all cells.

---

## MySQL Database Connection

Update your MySQL credentials inside the notebook:

```python
engine = create_engine(
    "mysql+pymysql://root:password@localhost/superstore"
)
```

Replace:
- `root`
- `password`
- `superstore`

with your own MySQL credentials.

---

## Future Improvements
Potential future enhancements:
- Sales forecasting
- Customer segmentation
- Machine learning integration
- Interactive Power BI dashboard
- Streamlit deployment

---

## Author
Nguyen Vu Minh Thu
