# WebScraping_Project

# 🧺 Washing Machine Market Analysis

## 📌 Project Overview

The **Washing Machine Market Analysis** project focuses on collecting, cleaning, and analyzing washing machine product data from Flipkart using Web Scraping techniques.

The main objective is to understand the washing machine market by analyzing product prices, brands, capacity, ratings, RPM, warranty, discounts, and machine types.

This project uses Python libraries for web scraping, data cleaning, data analysis, and visualization to generate meaningful business insights and recommendations.

## 🎯 Project Objectives

- Collect washing machine product information from Flipkart.
- Extract relevant product details using Web Scraping.
- Clean and preprocess the collected data.
- Handle missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Visualize product pricing, brands, ratings, and other features.
- Generate business insights and recommendations.

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language.
- **Jupyter Notebook** – Development environment.
- **Requests** – Sending HTTP requests.
- **BeautifulSoup** – Extracting information from HTML.
- **Pandas** – Data cleaning and manipulation.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Regular Expressions (Regex)** – Text cleaning and data extraction.

## 📊 Dataset Description

The dataset contains washing machine product information collected from Flipkart.

Important features include:

| Feature | Description |
|---|---|
| Brand | Washing machine brand |
| Capacity_kg | Washing machine capacity in kg |
| Price | Product selling price |
| Warranty | Product warranty information |
| Power_Rating | Power rating information |
| RPM | Spin speed of the washing machine |
| Discount | Product discount |
| Rating | Customer rating |
| Machine_Type | Top Load / Front Load / other available types |

*Note: The availability of individual columns depends on the information extracted from product listings.*

## 🔄 Project Workflow

1. **Business Understanding** – Define the problem and project objectives.
2. **Data Collection** – Scrape washing machine product information from Flipkart.
3. **Data Understanding** – Explore the collected dataset.
4. **Data Cleaning** – Handle missing values, duplicates, and inconsistent data.
5. **Feature Engineering** – Create additional useful columns using existing data.
6. **Exploratory Data Analysis (EDA)** – Analyze individual features and relationships between variables.
7. **Data Visualization** – Create charts to understand market trends.
8. **Business Insights** – Identify important patterns from the analysis.
9. **Recommendations** – Suggest business strategies based on the findings.

## 📈 Exploratory Data Analysis

The project explores the following areas:

- Brand-wise product distribution.
- Washing machine price distribution.
- Capacity vs. price analysis.
- Average price by brand.
- Customer rating analysis.
- RPM comparison.
- Discount analysis.
- Machine type distribution.
- Warranty analysis.

## 💡 Business Insights

The analysis aims to identify:

- Differences in pricing across brands.
- Relationships between washing machine capacity and price.
- Popular washing machine capacities.
- Price differences between machine types.
- Customer rating patterns.
- Differences in product specifications.
- Missing product information and its impact on analysis.

## 🚀 Business Recommendations

- Maintain products across different price ranges.
- Focus on popular washing machine capacities.
- Monitor competitor pricing.
- Highlight verified customer ratings.
- Provide complete product specifications.
- Use discounts strategically.
- Update market data regularly.
- Use market analysis for better inventory planning.

## 📁 Project Structure

```text
Washing-Machine-Market-Analysis/
│
├── Washing_Machine_Market_Analysis.ipynb
├── washing_machine_data.csv
├── cleaned_washing_machine_data.csv
├── visualizations/
│   ├── brand_analysis.png
│   ├── price_analysis.png
│   └── capacity_analysis.png
│
├── README.md
└── requirements.txt
```

*The filenames and visualization examples above are suggested. Update them to match your actual project files.*

## ▶️ How to Run This Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2:** Navigate to the project folder.

```bash
cd Washing-Machine-Market-Analysis
```

**Step 3:** Install the required libraries.

```bash
pip install requests beautifulsoup4 pandas numpy matplotlib seaborn jupyter
```

**Step 4:** Start Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open and execute `Washing_Machine_Market_Analysis.ipynb` cell by cell.

## ⚠️ Disclaimer

This project is created for educational and learning purposes. Product information is collected from publicly accessible Flipkart search listings. Product prices, discounts, ratings, and availability may change over time.

This project does not represent official market data from Flipkart.

## 👨‍💻 Author

**Chintala Sravan Kumar Goud**

B.Tech – Data Science

Interested in Data Science, Python, Machine Learning, Data Analytics, and Web Scraping.

## ⭐ Acknowledgement

Thanks to the Python open-source community and the developers of the libraries used in this project.
