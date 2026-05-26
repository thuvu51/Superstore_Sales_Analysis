# Superstore Sales Analysis Using SQL, Python, and Power BI

## Project Overview
This project analyzes Superstore retail sales data using SQL, Python, and Power BI to uncover insights related to revenue performance, customer behavior, profitability, discount strategies, and regional sales trends.

The project combines:
- SQL for data extraction and aggregation
- Python for data cleaning, exploratory data analysis (EDA), and visualization
- Power BI for interactive dashboard development and business reporting

The goal of this project is to support data-driven business decision-making through analytical insights and dashboard visualization.

---

## Business Problem
Retail businesses generate large volumes of transactional data, but raw data alone does not provide actionable insights. This project aims to identify key business drivers, evaluate sales performance, and generate strategic recommendations to improve profitability and operational efficiency.

---

## Project Objectives
- Analyze revenue performance across product categories and customer segments to identify key revenue drivers.

- Examine sales trends over time to understand customer purchasing behavior and growth patterns.

- Evaluate regional profitability to determine high-performing and underperforming markets.

- Investigate the relationship between discounts and profitability to assess the impact of pricing strategies.

- Identify top revenue-generating customers to support customer retention and loyalty strategies.

- Build an interactive Power BI dashboard for KPI monitoring and business performance analysis.

- Generate actionable business insights using SQL, Python, Power BI, and data visualization techniques to support data-driven decision-making.

---

## Dataset Description
The dataset contains retail transactional records including:

- Order Date
- Customer Name
- Product Name
- Category
- Segment
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
- Power BI

---

## Exploratory Data Analysis (EDA)

EDA was performed to:
- Analyze sales and profit distributions
- Identify outliers
- Explore correlations between variables
- Discover sales trends and customer behavior patterns

### Visualizations Used
- Histogram
- Boxplot
- Heatmap
- Bar Chart
- Line Chart
- Scatter Plot

---

## Power BI Dashboard

An interactive Power BI dashboard was developed to monitor business performance and visualize key business metrics.

### Dashboard Features
- Sales KPI tracking
- Profit KPI tracking
- Profit margin analysis
- Sales trend analysis
- Profit analysis by category
- Customer segment analysis
- Top customer analysis
- Interactive filtering and drill-down capabilities

---

## Business Questions

### 1. Which product categories and customer segments contribute the most to overall revenue?
Analyzed revenue performance across product categories and customer segments to identify key revenue drivers.

### 2. How do sales trends differ among customer segments over time?
Examined monthly sales trends across customer segments to understand purchasing behavior and growth patterns.

### 3. Which regions are the most profitable?
Compared regional profit performance to evaluate operational effectiveness and identify high-performing markets.

### 4. How do discounts impact profitability?
Investigated the relationship between discount levels and profit margins to assess pricing effectiveness.

### 5. Who are the top customers by revenue?
Identified high-value customers contributing the largest share of total revenue.

---

## Key Findings
- Technology products generated the highest overall revenue, particularly among Consumer and Corporate customer segments.

- Consumer customers demonstrated the most stable and consistent sales growth over time.

- Higher discount levels were associated with lower profitability, suggesting that excessive discounting may negatively affect profit margins.

- A small number of high-value customers contributed significantly to total revenue.

- The West region generated the highest overall profit among all regions.

---

## Business Recommendations
- Focus marketing and inventory investment on high-performing product categories such as Technology.

- Strengthen customer retention strategies for Consumer and Corporate customer segments due to their consistent revenue contribution.

- Expand business efforts in highly profitable regions while investigating operational inefficiencies in underperforming markets.

- Optimize discount strategies by limiting excessive discounts on low-margin products to improve profitability.

- Develop loyalty programs and personalized campaigns for top revenue-generating customers.

---

## Project Structure

```text
superstore-sales-analysis/
│
├── notebooks/
│   └── Superstore_Sales_Analysis.ipynb
│
├── dashboard/
│   └── Superstore_Sales_Dashboard.pbix
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
- Advanced Power BI dashboard enhancements
- Real-time data integration
- Automated KPI reporting
- Sales forecasting
- Advanced customer segmentation
- Machine learning integration
- Streamlit deployment

---

## Author
Nguyen Vu Minh Thu
