# 🏷️ TextileBiz Analytics: Smart Pricing & Market Analysis  

**TextileBiz Analytics** is an advanced **data-driven pricing optimization** solution designed for the textile industry. This project leverages **real-time price scraping, competitive market analysis, dynamic pricing strategies, and machine learning** to help businesses make informed pricing decisions.  

## 🚀 Features  

### 🔹 **Data Preprocessing & Cleaning**  
- Standardizes and prepares raw textile pricing data for analysis.  
- Removes missing values and normalizes column formats.  

### 🔹 **Competitor Price Scraping**  
- Extracts real-time pricing data from **Amazon & Google**.  
- Uses automated web scraping techniques with proxy support.  

### 🔹 **Pricing Analysis & Classification**  
- Identifies **overpriced, underpriced, and competitive** items.  
- Generates detailed pricing analysis reports.  

### 🔹 **Dynamic Pricing Optimization**  
- Applies **business rules** to adjust pricing based on competitors.  
- Ensures minimum profit margins and strategic price reductions.  

### 🔹 **Machine Learning Model for Price Prediction**  
- Trains a **Linear Regression Model** to predict optimized prices.  
- Factors in **cost price, competitor price, seasonality, and location**.  

### 🔹 **Power BI Dashboard for Insights**  
- Provides interactive **visual analytics** for pricing trends.  
- Showcases **competitor benchmarking** and **optimal price recommendations**.  

---

## 📂 Folder Structure  

```bash
TextileBiz-Analytics-Smart-Pricing-Market-Analysis/
│── data/
│   ├── Textile_data2.txt.csv  # Original raw dataset
│   ├── Enhanced_Textile_Dataset.csv  # Cleaned dataset
│   ├── Pricing_Analysis_Report.csv  # Pricing classification results
│   ├── Optimized_Pricing_Dataset.csv  # Adjusted pricing after rules
│   ├── Final_ML_Pricing_Dataset.csv  # ML-predicted optimal prices
│── models/
│   ├── trained_model.pkl  # Trained Machine Learning model
│── scripts/
│   ├── cleaning_dataset.py  # Data cleaning & preprocessing
│   ├── price_scraper.py  # Web scraping (Amazon & Google)
│   ├── price_analysis.py  # Competitive pricing classification
│   ├── optimize_price.py  # Dynamic pricing strategy implementation
│   ├── train_model.py  # Machine Learning model training
│── notebooks/
│   ├── TextileBiz_Analytics_Analysis.ipynb  # Jupyter Notebook with full pipeline
│── dashboards/
│   ├── Textile_Pricing_Dashboard.pbix  # Power BI Dashboard file
│── README.md  # Project documentation
│── requirements.txt  # Python dependencies


---






