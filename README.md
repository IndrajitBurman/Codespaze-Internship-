# Codespaze-Internship-
Customer Segmentation Analysis 
Customer segmentation analysis
Name: Indrajit Burman 
Problem statement:
This project involves analysing customer data to segment them based on their purchasing behaviour using clustering algorithms. The goal is to understand different types of customers and tailor marketing strategies accordingly.
Customer segmentation is crucial for businesses to target specific groups with personalized marketing, leading to higher customer satisfaction and retention. This project uses K-means and hierarchical clustering to segment customers based on various features such as age, income, spending score, and purchase frequency. 
The project requires python libraries such as: pandas, NumPy, matplotlib, seaborn, scikit learn
Approach: 
Data preprocessing, cleaning, EDA (Exploratory Data Analysis):
First load the dataset and understand the data. There are 9 columns and 1000 rows. Then I check the if there are any missing values, in the data there is no missing values and duplicate values. I check the statistics of the data, and found out I don’t need the ID column hence I drop it. Then I start with EDA, first I check with a histogram the valuation of gender and their value count and also the preferred category of the data according to the gender. I divide the age column into groups and visualize it with a bar chart, I did the same with income group for better understanding the relation between age groups and income range. Then I plot a pie chart to show the gender and preferred categories relationship. 
This is a customer segmentation analysis hence I have to segment with recency, frequency and monetary. I use standard scaler to standardize the recency, frequency and monetary of the data. 
Clustering method: 
1)	K-Means clustering 
First I use the k means clustering into two features such as frequency and monetary. I visualize the elbow curve to find the numbers of clusters then fit the k means clustering model and visualizing it through a scatterplot. 
Second, I use the k means clustering into recency and monetary and find their elbow curve and visualizing it through 2D scatterplot.
Third, I use k means clustering into all three features such as recency, frequency and monitory and find their elbow curve for the number of clusters and I find 5 clusters are more suitable and visualizing it through 3D scatterplot. 
2)	Hierarchical clustering:
I use dendrogram for finding the features and Euclidean distance. Then I build the model by using Agglomerative Clustering. And visualizing with a scatterplot and distributions of the clusters by a count plot. 
