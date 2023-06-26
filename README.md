# Retail Sales Analysis
This project focuses on performing data analysis and developing machine learning models for a retail company to gain insights into customer purchase behavior and improve sales strategies. The project utilizes the Apriori algorithm for performing basket analysis, a clustering model to study customer purchase behavior, and a classification model to predict product reordering.
## Table of Contents
- Introduction
- Requirements
- Data
- Methods
- Results
- Usage
- Contributing
- License

## Introuction
In this project, we aim to obtain information on our products orders  using exploratory analysis and identify products that are frequently purchased together using the Apriori algorithm, which is a classic algorithm for associative mining. This allows the retail company to understand the relationships between different products and potentially optimize product placement, promotions, and recommendations.

Furthermore, we develop a clustering model to gain insights into customer purchase behavior. By grouping customers based on their purchasing patterns, the retail company can tailor marketing strategies to different customer segments and provide personalized recommendations.

Lastly, a classification model is developed to predict whether a product is likely to be reordered or not. This information can help the retail company identify opportunities for increasing customer retention and improving inventory management.

## Requirements
To run this project, you need the following dependencies:
- Python 3.x
- Pandas
- Numpy
- Scikit-learn

## Data
The dataset used for this project consists of over 8 million rows historical transactional data from the retail company. It consists of 4 different datasets which departments data which shows department each product belongs to, Aisle data which shows the Aisle ofeach product, Product data and Order data. The dataset is stored in a CSV file named sales_data.csv.

## Methods
### Basket Analysis
To perform basket analysis, we utilize the Apriori algorithm, a widely used algorithm for mining frequent item sets. The algorithm allows us to identify associations between products that are frequently purchased together. By setting appropriate thresholds for support and confidence, we can extract meaningful rules that reveal these associations.
### Data Exploration and Clustering Analysis
We performed Data analysis to determine the most selling products and peak sales periods. To study customer purchase behavior, we employ a clustering model. By grouping customers based on their purchasing patterns, we can identify segments with similar preferences and behaviors. This helps in tailoring marketing strategies and personalizing recommendations for different customer groups. In this project, we use the k-means algorithm for clustering.
### Classification Model
To predict product reordering, we develop a classification model. This model is trained on historical data, including features such as customer purchasing history, product details, and order information. By analyzing these features, the model can determine whether a product is likely to be reordered or not. For this project, we explored Logistic regression, Decision trees, Random Forest and XGBoost classifiers. XGBoost gave us the best Accuracy

## Results
The results obtained from the analysis and models are as follows:
- Data Analysis: Identified the most selling products, most selling departs, peak hours of the days and days of the week for sales, and performing products in each department
- Basket Analysis: Identified frequent itemsets and association rules, revealing products that are frequently purchased together.
- Clustering Analysis: Grouped customers into distinct segments based on their purchasing patterns, allowing for targeted marketing strategies.
- Classification Model: Developed a model to predict product reordering, enabling proactive inventory management and customer retention strategies.

## Usage
To run the analysis and models, follow these steps:
- Ensure you have installed the required dependencies mentioned in the Requirements section.
- Place the dataset file sales_data.csv in the data directory.
