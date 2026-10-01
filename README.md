# 📱 Mobile Sales Data Analysis

An end-to-end **Data Analysis and Exploratory Data Analysis (EDA)** project based on mobile phone sales data. The project uses Python, Pandas, NumPy, Matplotlib and Seaborn to clean, explore, analyze and visualize sales and customer-related data.

## 🎯 Project Objectives

- Understand mobile sales performance across brands, models, cities and states.
- Analyze revenue, units sold, pricing and discounts.
- Compare Online and Offline sales channels.
- Study customer age, gender, ratings and payment methods.
- Analyze return patterns and product categories.
- Create meaningful visualizations and derive business insights.

## 📊 Dataset

- **Rows:** 10,918
- **Columns:** 24
- **Domain:** Mobile phone sales / retail analytics
- **Format:** CSV

The dataset is available in `data/mobile_sales_dataset.csv`.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Repository Structure

```text
mobile-sales-data-analysis/
│
├── data/
│   └── mobile_sales_dataset.csv
│
├── notebooks/
│   └── Mobile_Sales_Analysis.ipynb
│
├── docs/
│   ├── data_dictionary.md
│   └── project_summary.md
│
├── visualizations/
│   └── README.md
│
├── .gitignore
├── LICENSE
├── requirements.txt
└── README.md
```

## 🔍 Analysis Workflow

1. Import required libraries
2. Load the dataset
3. Understand dataset structure and data types
4. Check missing values
5. Check duplicate records
6. Perform data cleaning
7. Perform exploratory data analysis
8. Analyze sales and revenue
9. Analyze brands, channels and customer segments
10. Perform feature engineering
11. Create visualizations
12. Extract business insights
13. Summarize conclusions

## 📈 Key Analysis Areas

- Brand-wise sales and revenue
- Model-wise performance
- Year/month sales trends
- State and city analysis
- Online vs Offline channels
- Price segments and categories
- Network analysis (4G/5G)
- Discount analysis
- Customer age groups
- Gender distribution
- Payment methods
- Return analysis
- Customer ratings
- Revenue and units sold relationships

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/aniketbhadait019-cmd/mobile-sales-data-analysis
cd mobile-sales-data-analysis
```

### 2. Create a virtual environment (optional)

```bash
python -m venv venv
```

Windows:
```bash
venv\\Scripts\\activate
```

Linux/macOS:
```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Mobile_Sales_Analysis.ipynb
```

> The notebook currently references `mobile_sales_dataset.csv`. If running it directly from the `notebooks/` directory, either update the path to `../data/mobile_sales_dataset.csv` or keep a copy of the dataset beside the notebook.

## 💡 Project Outcome

This project demonstrates practical skills in **data cleaning, exploratory data analysis, feature engineering, statistical exploration and data visualization** using Python.

## 👨‍💻 Author

**Aniket Bhadait**

B.Sc. Computer Science | Data Analysis | Python | DevOps

## 📌 Future Improvements

- Build an interactive Power BI dashboard.
- Add automated data-quality checks.
- Add statistical hypothesis testing.
- Build a simple Streamlit analytics application.
- Add automated notebook execution using GitHub Actions.
