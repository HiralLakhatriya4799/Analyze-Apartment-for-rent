# Analyze-Apartment-for-rent
Analyze the data set with the k-mean clustering algorithm. 

### Project Overview 

This data analysis Project aims to provide insights into apartments for rent where we perform data preprocessing, the encoding of categorical variables, and the application of the K-means clustering algorithm.
The crucial aspect was dealing with missing or non-numeric values, demanding careful consideration to ensure the clustering results remained accurate. Moreover, visualizing the outcomes granted a profound understanding of how the algorithm effectively grouped the data points based on their distinct features.

### Data Source
Apartments for rent - The primary dataset used for the analysis of "apartments_for_rent_classified_10K.csv" file, containing more information.

UCL link - https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified

### Tools
Excel 
Juypter Notebook

### Import Libraries
 
import pandas as pd:  
import matplotlib.pyplot as plt: 

from sklearn.cluster import KMeans: This imports the KMeans class from the scikit-learn library, which is a popular machine-learning library in Python. KMeans is used for performing K-means clustering, a popular unsupervised learning algorithm. 

from sklearn.preprocessing import LabelEncoder: This imports the LabelEncoder class from scikit-learn's preprocessing module. The LabelEncoder is used for encoding categorical variables into numeric representations. It assigns a unique integer label to each unique category in a column, allowing machine learning algorithms to work with categorical data.

### Data Cleaning/ Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data Pre-Processing and uploading dataset
2. Hand Missing Values
3. Encoding categorical variables

### K-Mean Clustering

1. Plotting the Original data
2. Perform K-Mean Clustering
3. Plotting the Data 

### Clustering Result

This visualization Shows, multiple clusters are depicted using different colors, with data points having similar 'square_feet' and 'price_display' values grouped together. 

Cluster 1, represented by a violet color, comprises smaller-sized apartments with lower prices. This cluster likely includes affordable options for smaller living spaces. 
Cluster 2, depicted in green, likely contains larger-sized apartments with relatively lower prices and lower density. This cluster may represent larger apartments at a more budget-friendly range and possibly in less crowded locations.
Cluster 3, represented in blue, likely represents apartments with larger sizes and very high prices, with a density lower compared to Cluster 2. This cluster might include luxurious and spacious apartments in premium locations.
Cluster 4, indicated by a yellow color, may consist of apartments with small 
to medium sizes but higher prices compared to Cluster 1, and potentially with a higher density. These apartments could offer a balance between size and price and could be situated in relatively popular areas. 
The cluster centroids, marked by red 'x' symbols, show the average 'square_feet' and 'price_display' values for the data points within their respective clusters, providing insights into the central positions of each cluster. 

