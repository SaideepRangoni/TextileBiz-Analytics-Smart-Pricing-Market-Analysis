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

TextileBiz-Analytics-Smart-Pricing-Market-Analysis/
│── data/
│ ├── Textile_data2.txt.csv # Original raw dataset
│ ├── Enhanced_Textile_Dataset.csv # Cleaned dataset
│ ├── Pricing_Analysis_Report.csv # Pricing classification results
│ ├── Optimized_Pricing_Dataset.csv # Adjusted pricing after rules
│ ├── Final_ML_Pricing_Dataset.csv # ML-predicted optimal prices
│── models/
│ ├── trained_model.pkl # Trained Machine Learning model
│── scripts/
│ ├── cleaning_dataset.py # Data cleaning & preprocessing
│ ├── price_scraper.py # Web scraping (Amazon & Google)
│ ├── price_analysis.py # Competitive pricing classification
│ ├── optimize_price.py # Dynamic pricing strategy implementation
│ ├── train_model.py # Machine Learning model training
│── notebooks/
│ ├── TextileBiz_Analytics_Analysis.ipynb # Jupyter Notebook with full pipeline
│── dashboards/
│ ├── Textile_Pricing_Dashboard.pbix # Power BI Dashboard file
│── README.md # Project documentation
│── requirements.txt # Python dependencies


---

## 📊 Power BI Dashboard  
📌 The **Textile_Pricing_Dashboard.pbix** file in the `dashboards/` folder provides:  
✔ **Market Trends** | ✔ **Price Competitiveness** | ✔ **Optimized Pricing Insights**  

To use:  
- Open **Power BI Desktop**.  
- Load `dashboards/Textile_Pricing_Dashboard.pbix`.  
- Analyze **pricing trends, competitor insights, and ML-based pricing predictions**.  

---

## ⚙️ Configuration  
The `config/config.yaml` file stores key parameters, including:  
🔹 Pricing adjustment rules  
🔹 Web scraping settings  
🔹 Machine learning hyperparameters  

Modify this file to **customize your pricing strategy**.

---

## 🛠️ Technologies Used  
- **Data Processing:** Pandas, NumPy  
- **Web Scraping:** BeautifulSoup, Requests, Fake-UserAgent  
- **Machine Learning:** Scikit-Learn (Linear Regression)  
- **Visualization:** Power BI  
- **Development Tools:** Python, Jupyter Notebook  

---

## 📝 Testing & Validation  
- **Data Quality Checks** – Ensures clean and structured data.  
- **Model Evaluation** – Validates accuracy of pricing predictions.  
- **Competitor Benchmarking** – Verifies scraped data against actual market prices.  

---

## 📬 Contact & Support  
**Developed by:** Saideep Rangoni
- **Email:** saideeprangoni634@gmail.com
- **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com/in/saideep-rangoni-54abb9300/)

---

## 🚀 Transform Your Textile Business with Smart Pricing Strategies!  
