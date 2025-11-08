# 🌀 Web Scraping and Exploratory Data Analysis of Air Conditioners (Flipkart)

## 📘 About the Project
This project focuses on **web scraping and exploratory data analysis (EDA)** of Air Conditioner (AC) products listed on **Flipkart**, one of India’s leading e-commerce platforms. The primary goal is to extract, clean, and analyze product data to uncover insights about **pricing trends, brand performance, and customer preferences**.

Through this analysis, we aim to help businesses improve their **recommendation systems**, **optimize inventory**, and support **data-driven decisions** that enhance product visibility and customer satisfaction.

---

## 👨‍💻 About Me
I’m **Buddepu Vivek**, from **Innomatics Research Labs**, with a strong interest in **Exploratory Data Analytics (EDA)**.  
Skilled in data collection, cleaning, analysis, and visualization using Python and analytical tools.
I enjoy exploring real-world datasets to uncover insights that support better business strategies.

---

## 🧩 Business Problem
Flipkart’s AC product data and customer feedback are spread across multiple formats and pages, making it difficult to:  
- Analyze **sales trends** and **brand performance**  
- Understand **customer preferences**  
- Recommend products based on **usage needs**, **room size**, and **energy efficiency**

Hence, a **unified data analytics system** is required to merge and analyze the data to improve decision-making and customer experience.

---

## 🎯 Project Objectives
- Scrape product data (Brand, Price, Ratings, Specifications) from Flipkart.  
- Perform **data cleaning** and **transformation** for analysis.  
- Conduct **EDA** using visualization libraries to identify pricing patterns, brand trends, and power usage insights.  
- Provide **business recommendations** to improve sales performance.

---

## 🧰 Tools & Libraries Used
- **Python**
- **BeautifulSoup** (Web Scraping)
- **Requests**
- **Pandas**, **NumPy** (Data Cleaning & Manipulation)
- **Matplotlib**, **Seaborn** (Data Visualization)
- **Regex** (Data Extraction)

---

## 🧹 Data Cleaning Steps
- Standardized brand names and corrected inconsistent entries.  
- Converted categorical columns like `Model_Year`, `Star_Rating`, `Price_After_Discount` into numeric formats.  
- Detected and handled **missing values** using mean/mode imputation.  
- Removed **duplicates** and validated data types.  
- Ensured clean and structured data ready for visualization and insights.

---

## 📊 Data Visualization & Insights

### 🔹 Univariate Analysis
- **Histogram**: Price distribution lies between ₹25,000–₹45,000; ACs above ₹60,000 are rare and premium.  
- **Count Plot**: Most ACs have **3-star or 5-star** ratings—showing efficiency preferences.  
- **Pie Plot**: Highlights the proportion of room sizes suitable for various AC models.  
- **Distribution Plot**: Annual power usage is positively skewed; most ACs consume **500–1500 units annually**.

### 🔹 Bivariate Analysis
- **Bar Plot**: Brands like **LG, Daikin, Toshiba, General** are costlier; discount offers could improve their sales.  
- **Reg Plot**: ACs priced ₹25,000–₹60,000 generally have ratings between **4.0–4.5**. Improving efficiency may raise sales.  
- **LM Plot**: Shows positive correlation between **Capacity** and **Price**. Market differently based on room size and capacity.  
- **Bar Plot (Power vs Room Size)**: No clear relation found; manufacturers could optimize power usage by room size.

### 🔹 Multivariate Analysis
- **Heatmap**:  
  - Strong positive correlation between **Capacity** and **Price**.  
  - **Discount %** negatively correlated with **Price** — suggesting larger models benefit from discounts.  
- **Scatter Plot**: Higher capacity and star-rated ACs tend to be more expensive, indicating premium energy-efficient products.  
- **Box Plot**: ACs with higher star ratings and longer warranties are costlier — offering warranty-based promotions could build trust

---

## 🧠 Challenges Faced
- Dynamic Flipkart webpage — frequent reloading and inconsistent HTML structure.  
- Missing or incomplete product details during scraping.  
- Handling duplicates and noisy data.  
- Slow extraction due to pagination and dynamic elements.  
- Selecting visuals that effectively communicate business insights.

---

## ✅ Conclusion
This project successfully converted Flipkart’s AC product data into **clear, actionable insights**.  
By analyzing prices, features, and customer ratings, we identified **market trends and customer preferences**, which can help:  
- Buyers make **informed purchase decisions**  
- Sellers **optimize pricing strategies**  
- Businesses improve **inventory and recommendation systems**

---

## 📚 Learning Outcomes
- End-to-end understanding of the **data analysis workflow**:  
  **Web Scraping → Data Cleaning → EDA → Visualization**  
- Improved proficiency in **Python libraries** for data analytics.  
- Gained insights into **business-oriented data storytelling**.

---

### 🏷️ Author
**Buddepu Vivek**  
📍 Data Analyst | Innomatics Research Labs  
📧 [buddepuvivek2001@gmail.com]  
🔗 [https://www.linkedin.com/in/buddepu-vivek/]
