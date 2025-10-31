# 📊 Vendor Data Performance Analysis

This project focuses on **evaluating vendor performance** through **data-driven insights**.  
It involves cleaning and analyzing procurement datasets, identifying top-performing vendors, and visualizing key metrics such as **purchase contribution**, **order frequency**, **cost efficiency**, and **inventory trends**.  

The insights generated support **strategic procurement decisions**, **cost optimization**, and **business intelligence initiatives**.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-------------|----------|
| 🐍 **Python** | Data cleaning, EDA, and predictive modeling |
| 🗄️ **SQLite** | Lightweight database management |
| 📊 **Power BI** | Interactive dashboards and visual analytics |
| 📘 **Excel** | Data preprocessing and validation |
| 🎨 **Figma** | Dashboard design and prototyping |
| 🧠 **Git / GitHub** | Version control and project management |

---

## 📈 Key Features

- 🔍 Conduct **Exploratory Data Analysis (EDA)** on vendor, purchase, and sales datasets  
- ⚠️ Identify **key risk indicators** such as missed payments and high credit utilization  
- 📉 Develop **interactive dashboards** for vendor performance, sales trends, and inventory levels  
- 💡 Generate **actionable insights** for procurement optimization and cost reduction  
- ☁️ Enable **real-time reporting** via Power BI Service  

---

## 📂 Dataset

The full dataset is hosted on **Kaggle** due to GitHub size constraints.  

**Kaggle Dataset:** [Vendor Performance Data](https://www.kaggle.com/datasets/harshmadhavan/vendor-performance-analysis)

### 🔽 Download via Kaggle CLI
```bash
pip install kaggle
# Place kaggle.json in:
# Windows: C:\Users\<you>\.kaggle\
# macOS/Linux: ~/.kaggle/

kaggle datasets download -d harshmadhavan/vendor-performance-analysis -p data/ --unzip
📁 Files Included

purchases.csv

sales.csv

begin_inventory.csv

end_inventory.csv

purchase_prices.csv

vendor_invoice.csv

vendor_sales_summary.csv

🗂️ Project Structure
Vendor-Performance-Analysis/
│
├── data/                      # Dataset folder (excluded from Git)
├── logs/                      # Log files
├── scripts/                   # Python scripts
│   ├── get_vendor_summary.py  # Merges and summarizes data
│   └── ingestion_db.py        # Handles database ingestion
├── .gitignore                 # Files and folders to ignore in Git
├── EDA.ipynb                  # Exploratory Data Analysis notebook
├── Untitled.ipynb             # Additional experiments
├── vendor_Performance.pbix    # Power BI dashboard
├── inventory.db               # SQLite database
└── README.md                  # Project documentation

⚡ Usage Instructions

Download the dataset from Kaggle (see Dataset section above).

Run Python scripts from the scripts/ directory for ETL and summary generation.

python scripts/get_vendor_summary.py


Open the Power BI dashboard:

Load vendor_Performance.pbix

Connect to inventory.db if prompted

Explore interactive dashboards to gain actionable insights on vendor performance and procurement trends.

“Transforming procurement data into measurable business intelligence.”
