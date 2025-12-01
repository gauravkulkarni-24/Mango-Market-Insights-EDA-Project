# 🍋 Mango Market Price Analysis — Web Scraping + EDA 

## 📘 Project Overview
This project focuses on **real-world data extraction and analysis** by scraping mango market price data that publishes agricultural commodity prices across various markets.

Unlike traditional datasets, this project begins by collecting raw data directly from the web, cleaning it, preparing it, and then performing **Exploratory Data Analysis (EDA)** to uncover trends and market patterns.

This project strengthens my skills in:
- Web Scraping  
- Data Cleaning  
- Real-time Dataset Building  
- Exploratory Data Analysis  
- Visualization & Insight Generation  

---

## 🛠 Technologies & Libraries Used

### **Web Scraping**
- `requests`
- `BeautifulSoup`
- `lxml`

### **Data Analysis**
- `pandas`
- `numpy`

### **Data Visualization**
- `matplotlib`
- `seaborn`

### Environment
- Jupyter Notebook

---

## 📂 Project Structure



---

### Steps:
1. Sent HTTP requests to the AGMARKNET endpoint  
2. Extracted key information using BeautifulSoup  
3. Captured commodity name, market, state, price ranges, arrivals  
4. Cleaned the extracted raw text  
5. Stored everything into a structured DataFrame  
6. Exported final CSV to `/data/mango_market_data.csv`  

---

## 🧹 Data Cleaning & Preparation
Performed detailed cleaning:
- Removed inconsistent price formats  
- Converted min/max/modal price fields to numeric  
- Eliminated duplicates  
- Standardized missing values  
- Cleaned market & state names  
- Handled outliers  

---

## 📊 Exploratory Data Analysis (EDA)
Visualizations were created to understand:

### **1️⃣ Price Distribution Across Markets**
- Histogram & KDE plots  
- Min, Max, and Modal Price comparison  

### **2️⃣ Market-wise & State-wise Price Variation**
- Barplots  
- Boxplots  

### **3️⃣ Relationship Between Arrivals & Price Movement**
- Scatterplots  
- Trend analysis  

### **4️⃣ Correlation Heatmap**
- Understanding connections between prices, arrivals, and other variables  

---

## 🔍 Key Insights

### 🍋 **Price Behavior**
- Markets with **higher arrivals** tend to have **lower modal prices**
- Significant price variation across states indicates supply-chain and demand differences

### 🍃 **Regional Trends**
- Southern states showed **more stable pricing patterns**
- Some regions had drastic fluctuations due to seasonal effects

### 📈 **Demand–Supply Dynamics**
- A clear inverse relationship between arrivals and price  
- Modal price proved more reliable than average price in capturing market trends  

---

## 🚀 Learnings & Takeaways
This project helped me master:

✔ Real-world data extraction  
✔ Understanding and cleaning messy datasets  
✔ Building a fully controlled dataset end-to-end  
✔ Visualizing economic trends through EDA  
✔ Strengthening data storytelling  

This was an important step in becoming a complete data analyst —  
one who can **collect, clean, analyze, and interpret** data independently.

---

## 📂 Notebook & Code
All code, analysis, and visualizations can be found inside:
- `/notebooks/Web_Scraping_Project.ipynb`
- `/data/mango_market_data.csv`
- `/images/` (for visual outputs)

---
