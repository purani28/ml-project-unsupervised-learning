# machine_learning_project-unsupervised-learning

## Project Goals
This goal of this project is to apply unsupervised learning techniques to the "Wholesale Data" dataset to uncover patterns in grocery product sales and group similar data points. 
Key tasks include:
Exploratory Data Analysis (EDA): Cleaning the dataset, analyzing variable relationships, handling missing values and outliers, and performing feature engineering.
Unsupervised Learning: Utilizing K-means clustering, hierarchical clustering, and PCA to identify customer patterns, determine the optimal number of clusters, and visualize insights.
The goal is to extract actionable insights from the data and communicate findings effectively through visualizations and metrics, enabling stakeholders to make informed business decisions.

## Process
The project began with Exploratory Data Analysis (EDA), involving data cleaning, outlier removal, and visualizations to uncover trends and relationships. The data was then standardized using StandardScaler to prepare it for clustering. K-Means clustering identified optimal customer segments using the Elbow Method, which were further validated through hierarchical clustering. Finally, dimensionality reduction with PCA simplified data visualization, and the resulting clusters were analyzed to extract actionable business insights.

## Results
- The analysis identified four distinct customer segments based on spending patterns, highlighting differences such as preferences for fresh produce versus cleaning supplies. 
- Strong correlations were observed among Milk, Grocery, and Detergents_Paper, while Fresh and Frozen categories showed weaker relationships. 
- Clustering revealed actionable insights, distinguishing customers focused on specialty products from those with balanced spending. 
- PCA visualization further validated the clusters, enhancing interpretability and clarity.

## Chalanges
- Handling Outliers: Many variables exhibited extreme values, requiring careful preprocessing.
- Data Imbalance: Skewed distributions in spending categories required normalization and scaling.

## Future Goals
- Explore supervised learning to predict future purchases or behavior based on customer characteristics.
- Time-Series Analysis: Analyze customer spending patterns over time to identify trends, seasonality, and changes in preferences.