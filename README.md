# E-Commerce Sales Performance Analytics
**Future Interns Data Science & Analytics: Task 1 (2026)**

## Objective
Analyze a real-world e-commerce dataset to uncover revenue trends, 
top-performing products, and regional performance, then present findings 
in a client-ready Power BI dashboard.

## Project Structure
FUTURE_DS_01/

├── data/

│   ├── raw/                        # Original downloaded dataset

│   └── cleaned/                    # Cleaned, Power BI-ready CSV

├── notebooks/

│   └── ECommerce_Sales_Analytics.ipynb   # EDA notebook

├── outputs/                        # Generated charts

├── requirements.txt

└── README.md
## 📦 Dataset
UCI E-Commerce Orders Dataset  
Source: https://www.kaggle.com/datasets/carrie1/ecommerce-data  
~541,000 transactions from a UK-based online retailer (2010–2011)

## 🛠️ Tools
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Power BI Desktop

## 🚀 How to Run
1. Clone the repo and navigate into it
2. Create and activate a virtual environment
```bash
   python -m venv .venv
   .venv\Scripts\Activate.ps1
```
3. Install dependencies
```bash
   pip install -r requirements.txt
```
4. Place the downloaded dataset in `data/raw/` and rename it `raw_ecommerce.csv`
5. Open and run the notebook
```bash
   jupyter notebook notebooks/ECommerce_Sales_Analytics.ipynb
```
6. The cleaned CSV will be saved to `data/cleaned/clean_ecommerce.csv`
7. Import that CSV into Power BI to build the dashboard

## EDA Outputs
| Chart | Description |
|---|---|
| `monthly_revenue.png` | Revenue trend by month |
| `top_products.png` | Top 10 products by revenue |
| `top_countries.png` | Top 10 countries by revenue (ex UK) |
| `day_of_week.png` | Revenue by day of week |

## Key Insights
To be updated after Power BI dashboard is complete.

## Deliverables
- Cleaned dataset (`data/cleaned/clean_ecommerce.csv`)
- EDA notebook with documented analysis
- Power BI dashboard (link to be added)
- This README

## Dashboard Preview
![Dashboard](powerbi/ecommerce_dashboard_screenshot.png)

## Key Insights
- **£8.89M** total revenue generated across 18,532 orders
- Revenue peaks sharply in **Q4 (Oct–Dec)**, accounting for ~36% of annual revenue
- **PAPER CRAFT LITTLE BIRDIE** is the top product at £168K revenue
- **Netherlands and EIRE** are the strongest international markets outside the UK
- **Thursday** is the highest revenue day; Sunday is the weakest

## Deliverables
- [x] Cleaned dataset (`data/cleaned/clean_ecommerce.csv`)
- [x] EDA notebook with documented analysis (`notebooks/`)
- [x] Power BI dashboard (`powerbi/ecommerce_dashboard.pbix`)
- [x] Dashboard PDF export (`powerbi/ecommerce_dashboard.pdf`)