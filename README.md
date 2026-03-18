## 💻 Laptop Pricing & Market Trend Analysis

### 📌 Project Overview
The Laptop Pricing & Market Trend Analysis project is an end-to-end data analytics project that focuses on analyzing laptop pricing patterns using real-world e-commerce data.

This project involves web scraping, data cleaning, exploratory data analysis (EDA), and statistical testing to uncover the key factors influencing laptop prices and generate meaningful business insights.

### 🎯 Project Objectives
* Collect real-time laptop data using web scraping
* Design a clean and structured dataset
* Analyze how features like RAM, SSD, processor, and brand affect pricing
* Identify key pricing drivers and market trends
* Generate actionable business insights

### 🗂️ Dataset Overview
Total Records: 984 laptop variants

Features Included:
* Brand
* Processor
* Operating System
* RAM & RAM Type
* SSD Storage
* Display
* Selling Price
* Original Price
* Discount
* Rating

### 🛠️ Technologies Used
* Python
* Selenium (Web Scraping)
* Pandas & NumPy (Data Processing)
* Matplotlib & Seaborn (Visualization)
* Statistical Analysis (ANOVA, Correlation)

### 🧹 Data Cleaning & Preprocessing
* Removed unwanted symbols and text from columns
* Converted data into appropriate numerical formats
* Extracted structured values using Regex
* Handled missing values
* Removed duplicate records
* Ensured data consistency and reliability

### 📊 Exploratory Data Analysis (EDA)
#### 📅 1. Price Distribution
* Most laptops fall between ₹40,000 – ₹80,000
* Right-skewed distribution
* Premium laptops create outliers

#### 🏢 2. Brand Insights
* ASUS & HP dominate the market in volume
* Apple & Microsoft represent premium pricing segment
* Budget and premium brands show clear price segmentation

#### 💻 3. Feature Impact on Price
* Strong impact: RAM, SSD, Processor
* Weak impact: Display size, Ratings

#### 💾 4. Storage Analysis
* Higher SSD → Higher price
* Most common configurations: 512GB & 1TB

### 📉 Statistical Analysis
#### ✔️ 1. Brand vs Price (ANOVA Test)
Result: Significant impact

Conclusion: Laptop prices vary across brands

#### ✔️ 2. RAM vs Price (Correlation Test)
Correlation: ~0.64 (Positive)

Conclusion: Higher RAM leads to higher price

#### ❌ 3. Display Size vs Price
Result: No significant relationship

Conclusion: Display size does not influence pricing

### 📊 Key Insights
* Mid-range laptops dominate the market
* Performance features strongly influence pricing
* Premium laptops create price outliers
* Brand reputation impacts pricing strategy

### 💡 Business Insights
* Focus on 8GB–16GB RAM laptops (high demand segment)
* Optimize pricing for mid-range configurations
* Highlight key specifications for better customer decisions
* Use strategic discounts to improve sales performance

### ⚠️ Challenges Faced
* Cleaning unstructured scraped data
* Handling missing values and outliers
* Extracting features from raw text data
* Choosing appropriate statistical methods

#### 🚀 How to Run the Project
* Install required libraries
* Run the web scraping script (Selenium)
* Load dataset into Jupyter Notebook
* Perform EDA and statistical analysis

### 📈 Project Impact
This project helps to:
* Understand laptop pricing trends
* Support data-driven purchasing decisions
* Improve business pricing strategies
* Analyze customer demand patterns

#### 📚 Learning Outcomes
Through this project, I gained hands-on experience in:
* Web scraping using Selenium
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Statistical analysis and hypothesis testing

Deriving business insights from real-world data
