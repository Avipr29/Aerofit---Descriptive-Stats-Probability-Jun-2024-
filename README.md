# Aerofit---Descriptive-Stats-Probability-Jun-2024-

# 📊 Aerofit: Descriptive Statistics & Probability  

## 🏋️ About Aerofit  
Aerofit is a leading brand in the fitness equipment industry, offering a range of treadmills, exercise bikes, gym equipment, and fitness accessories to cater to diverse customer needs.  

## 🏢 Business Problem  
The Aerofit market research team aims to identify characteristics of the target audience for each type of treadmill to enhance product recommendations for new customers. The study explores whether customer demographics influence treadmill choices.  

### 🔍 Objectives  
1. Perform descriptive analytics to create customer profiles for each Aerofit treadmill.  
2. Construct two-way contingency tables to compute marginal and conditional probabilities and analyze their business impact.  

## 📂 Dataset  
The dataset contains information on individuals who purchased a treadmill from Aerofit stores in the past three months.  

### 📌 Features:  
- **Product Purchased**: `KP281`, `KP481`, or `KP781`  
- **Age**: Customer’s age (in years)  
- **Gender**: Male/Female  
- **Education**: Years of education completed  
- **Marital Status**: Single or partnered  
- **Usage**: Average weekly treadmill usage  
- **Income**: Annual income (in $)  
- **Fitness**: Self-rated fitness level (1 - Poor, 5 - Excellent)  
- **Miles**: Average weekly distance covered on the treadmill  

## 🏷️ Product Portfolio  
| Product  | Price  | Target Audience  |  
|----------|--------|-----------------|  
| **KP281** | $1,500 | Entry-level, budget-conscious buyers |  
| **KP481** | $1,750 | Mid-tier customers, fitness enthusiasts |  
| **KP781** | $2,500 | Premium users, high-income & fitness-driven customers |  

## 🛠️ Approach & Methodology  
### 🔹 Data Analysis Steps  
✔ Import dataset and explore structure & characteristics  
✔ Detect outliers using boxplots and statistical summaries  
✔ Analyze impact of features like marital status and age on product purchases  
✔ Compute and visualize marginal & conditional probabilities using `pandas.crosstab`  
✔ Perform correlation analysis with heatmaps & pair plots  
✔ Derive business insights and customer segmentation  

### 📊 Insights & Findings  
#### **Univariate Analysis**  
✅ Majority of buyers are in their **mid-20s**, with strong fitness interests.  
✅ Most customers use the treadmill **at least 3 times a week** and cover **~100 miles per week**.  
✅ **KP281 is the most purchased model** (44.44% of sales).  

#### **Bivariate Analysis**  
✅ **Higher-income, highly-educated individuals** tend to buy **KP781**.  
✅ **Married customers (59.44%)** are more likely to purchase a treadmill, likely due to time constraints & lifestyle choices.  
✅ Customers who **cover extreme distances (200-350 miles/week)** prefer KP781, indicating a premium, performance-oriented segment.  

#### **Probability Analysis**  
✔ Used contingency tables to compute probabilities of product selection based on gender, income, and fitness level.  
✔ Example: **Probability of a male customer purchasing KP781** was calculated using conditional probability.  

## 📌 Business Recommendations  
### 📌 **KP281 - Entry-Level Model**  
🎯 Target **students & young individuals** with limited income.  
📢 Promote via **social media influencers** & student discounts.  
🏫 Organize **college exhibitions & fitness awareness campaigns**.  

### 📌 **KP481 - Mid-Tier Model**  
🎯 Use **price anchoring** to make KP481 appear as the best-value option.  
📢 Market as a **better alternative** to KP281, offering enhanced features.  

### 📌 **KP781 - Premium Model**  
🎯 Target **high-income fitness enthusiasts** & **athletes**.  
📢 Market as a **luxury fitness product** with features like **mobile integration**.  
🤝 Endorse with **sports personalities & fitness trainers**.  

## 🔧 Tools & Technologies  
- **Python**: `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `SciPy`  
- **Statistical Methods**: Descriptive analysis, contingency tables, probability computations  
- **Visualization**: Count plots, histograms, heatmaps, pair plots  

## 📈 Key Takeaways  
✔ Data-driven customer profiling enables **targeted marketing** and **product positioning**.  
✔ **Probability & statistical analysis** help understand **customer preferences** and **predict purchasing behavior**.  
✔ Aerofit can optimize marketing strategies by aligning products with **income, fitness levels, and demographic factors**.  

---

