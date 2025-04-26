🍷 Exploratory Data Analysis (EDA) of Red Wine Quality Dataset using Python

🔍 Project Overview
This project delves into the exploratory data analysis of the Red Wine Quality Dataset, aiming to uncover patterns and relationships between various chemical features of wine and its quality rating. By leveraging Python libraries such as Pandas, Matplotlib, and Seaborn, this analysis provides valuable insights into the factors that influence wine quality and prepares the dataset for potential future predictive modeling.

📁 Dataset Description
Source: Kaggle – Red Wine Quality Dataset

Total Records: 1599

Features: 11 chemical input variables and 1 output variable (wine quality)

Target Variable: Quality (rated between 3 and 8 in this dataset)

Input Features:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

🧹 Data Cleaning
✅ No missing values found in the dataset

✅ Removed 240 duplicate records to ensure accuracy and consistency

✅ Verified data types and performed initial summary statistics

📊 Exploratory Data Analysis
📌 1. Statistical Summary
The average wine quality is approximately 5.64

Quality ratings range from 3 to 8

Majority of wines are rated 5 or 6, indicating a skew toward average-quality wines

📌 2. Visual Analysis
A) 📈 Correlation Heatmap
Strongest positive correlation: Alcohol (with quality)

Other positively correlated variables: Citric Acid, Fixed Acidity

Negatively correlated: Volatile Acidity, Free Sulfur Dioxide, and pH

Visualized using Seaborn heatmap for quick pattern recognition

B) 📊 Bar Plot of Quality Distribution
The wine quality scores are imbalanced, with the highest concentration around quality 5 and 6

Indicates a class imbalance that is important for understanding bias in the dataset

C) 📉 Histogram – Alcohol Distribution
Alcohol content is right-skewed

Most wines fall within 9–12% alcohol content, fewer above 12%

Indicates fewer high-alcohol wines in the dataset

D) 🔗 Pair Plot
Used for univariate, bivariate, and multivariate analysis

Helps in visualizing pairwise relationships between features

Showcases potential linear relationships, especially between alcohol, density, and quality

E) 📦 Box Plot – Alcohol vs Quality
Wines rated higher (7 or 8) tend to have higher alcohol content

Wines rated lower (3 to 5) show lower alcohol content

Several outliers observed in wines rated as 5

F) 🧪 Scatter Plot – pH vs Alcohol (Hue: Quality)
Reveals how alcohol and pH interact with wine quality

Lower pH = higher acidity; most values range between 3.0 to 3.6

Alcohol ranges from 9% to 14%, and higher quality wines tend to be spread across a wider alcohol range

🛠️ Tools & Libraries Used
Python (Jupyter Notebook)

Pandas – for data handling and preprocessing

Matplotlib – for creating static plots

Seaborn – for advanced statistical data visualization

NumPy – for numerical operations

📌 Key Insights
Alcohol is the most positively correlated feature with wine quality

Volatile Acidity shows a strong negative correlation, indicating its inverse relation to quality

The dataset is class-imbalanced, with most wines clustered around a quality of 5 or 6

There is a clear visual relationship between higher alcohol content and better quality ratings

Outliers exist and should be considered when preparing for further analysis or modeling

