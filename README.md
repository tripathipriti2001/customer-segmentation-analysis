# Customer-segmentation-Analysis
This project is a customer segmentation analysis of customers of an FMCG store. The goal of the project is to create clusters or groups of these customers to foster marketing decisions and for better undertsanding of customer characteristics which could ultimately impact sales and profit generation.



![Alt text](img.png)

# Installation 
The code requires:
* `python 3 and above`
* `pandas`
* `sklearn`
* `powerbi desktop` for visualization purposes 

This project focuses on clustering analysis, a key unsupervised machine learning technique used to group similar data points. Using the k-means algorithm, we segmented a 2000-instance dataset into four distinct customer groups based on seven key features. K-means was chosen for its simplicity and effectiveness in clustering. To enhance data exploration, we built an interactive Power BI dashboard where users can easily analyze differences between customer segments, such as variations in average income. The dashboard, with slicers for dynamic filtering, enables intuitive insights into customer behavior patterns useful for marketing, recommendations, and more.


# Data Gathering 
Data was gathered from kaggle.

# File Description 
The folder contains:
* `a data folder` that contains the original dataset and that generated after creating the clustering model that served as an input for the powerbi dashboard
* `customer.ipynb` a jupyter notebook of the clustering model creation 
* `customer_segment.pbix` the powerbi dashboard created- this should be opened with powerbi desktop

