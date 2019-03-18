# Identify Customer Segments

# Installation
The libraries/packages used are:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- math

# Project Motivation
The project is the third project for the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) - Term1. 

The dataset for this project is provided by Bertelsmann Arvato Analytics, and represents a real-life data science task.

The goal of this project is to apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.

# File Descriptions
- This notebook `Identify_Customer_Segments_Final.ipynb` includes the process of cleaning messy survey data, transforming features, applying PCA for feature reduction and clustering the data based on PCA results to identify target customers.
- `Identify_Customer_Segments_Final.html` is the html output of the `Identify_Customer_Segments_Final.ipynb` juypter notebook
- `scree_plot_pca.jpg` is the PCA scree plot picture since it is too wide to be seen clearly in the notebook

# Results
The highlights of the project are:
- Clean the messy survey data from the real world and transforming features based on business understanding
- Implement PCA algorithm and interpret the principal components
- Cluster the data based on the principal components. Analyze the principal components in each cluster to identify the target marketing customers.

The project identifies the segments of the population that are relatively popular with the mail-order company are those who are:
- wealthier, have stable housing (low in movement), live in a wealthier and less populated neighborhood
- older, more conservative in money spending
- male, less dreamful, less family-minded and less social-minded

The segments of the population that are relatively unpopular with the company are those who are:
- low-income earners, poor and live in a poorer and more populated neighborhood
- less conservative, younger, not a money saver and not very religious
- female, less combative and less dominant

# Licensing, Authors, Acknowledgements
1. Credits to https://github.com/paawan01/Titanic_dataset_analysis for the readme template

