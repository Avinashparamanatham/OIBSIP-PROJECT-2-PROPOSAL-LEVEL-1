# Customer Segmentation Analysis

## Overview
This project performs customer segmentation analysis for an e-commerce company using machine learning techniques. By analyzing customer behavior and purchase patterns, we group customers into distinct segments to inform targeted marketing strategies and improve business decisions.

## Project Description
This data analytics project aims to:
- Analyze customer behavior and purchase patterns
- Identify distinct customer segments using clustering algorithms
- Provide actionable insights for targeted marketing strategies
- Enhance customer satisfaction through personalized approaches
- Optimize overall business strategies based on segment characteristics

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/customer-segmentation.git

# Navigate to the project directory
cd customer-segmentation

# Install required packages
pip install -r requirements.txt
```

## Data Description
The dataset includes the following features:
- CustomerID: Unique identifier for each customer
- Genre: Customer's gender
- Age: Customer's age
- Annual Income (k$): Customer's annual income in thousands of dollars
- Spending Score (1-100): Score assigned based on customer behavior and spending nature


## Methodology
1. **Data Preprocessing**
   - Data cleaning and handling missing values
   - Feature scaling and normalization
   - Exploratory data analysis

2. **Customer Segmentation**
   - K-means clustering implementation
   - Optimal cluster number determination using:
     - Elbow method
     - Silhouette analysis

3. **Visualization and Analysis**
   - Cluster visualization using scatter plots
   - Customer behavior analysis within segments
   - Demographic analysis of segments

## Results
The analysis identified distinct customer segments based on:
- Spending patterns
- Income levels
- Age distribution
- Gender distribution

Key visualizations include:
- Customer segment scatter plots
- Distribution of features within segments
- Demographic breakdowns
