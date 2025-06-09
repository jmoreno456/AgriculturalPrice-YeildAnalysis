# AgriculturalPrice-YieldAnalysis

This project analyzes produce shopping trends using a dataset of consumer transactions. The goal is to uncover patterns in produce purchasing behavior, such as frequent item combinations, seasonal variations, and insights that can help optimize inventory or marketing strategies.


## 📁 Dataset Overview
The dataset contains detailed records of produce purchases, including items like fruits, vegetables, and other fresh goods. The data includes:

- Unique transaction IDs
- Names of produce items
- (Potentially) timestamps or customer segments


## 🎯 Objective
The main objectives of this analysis are:
- Identify the most frequently purchased produce items
- Analyze common produce item combinations (e.g., apples and bananas often bought together)
- Visualize trends and patterns that can inform retail decisions


## 📈 Analysis Workflow
1. **Import Libraries**  
   Standard data science libraries like `pandas`, `matplotlib`, and `seaborn` were used.

2. **Data Cleaning and Preparation**  
   - Combined rows or columns to create transaction baskets  
   - Handled missing values and duplicates

3. **Exploratory Data Analysis (EDA)**  
   - Most common produce items
   - Co-occurrence heatmaps of item pairs
   - Visualizations for frequency distributions

4. **Pattern Discovery**  
   - Used association rule mining (e.g., Apriori algorithm from `mlxtend`)
   - Calculated support, confidence, and lift for popular item pairs


## 📊 Key Results
- **Top Purchased Items**: Apples, Bananas, Tomatoes, and Carrots
- **Common Combos**: Bananas & Strawberries, Lettuce & Tomatoes
- **Insights**:
  - High lift values between certain item pairs suggest strong co-purchasing behavior
  - Potential for bundling or co-promotions in stores


## 📌 Conclusions
- Several produce items consistently appear together in transactions, indicating stable consumer behavior.
- Association rules can help guide marketing strategies like combo deals or aisle layouts.
