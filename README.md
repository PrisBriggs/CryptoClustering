# CryptoClustering

Georgia Tech Data Science and Analytics BootCamp - May 2023

Homework Module 19 - Unsupervised Machine Learning - Crypto Clustering Challenge
By Priscila Menezes Briggs

Challenge history
In this challenge, Python and unsupervised learning were used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Resource
CSV file with coin IDs and its values for price change percentage over time.

Methodology

- Data was normalized with StandardScaler module from scikit-learn.
- Best value for K was found using the elbow method.
- Cryptocurrencies were clustered with K-means using the scaled data.
- Clusters were optmized using Principal Component Analysis.
- Best value for K was then found using PCA data.
- Cryptocurrencies were clustered with K-means using the PCA data.
- Comparison plots were created to evaluate the differences between those models. 

Questions that were answered with this project:

- What is the best value for k using the scaled data?
- What is the best value for k when using the PCA data? Does it differ from the best k value found using the original (scaled) data?
- What is the impact of using fewer features (after PCA modeling) to cluster the data using K-Means?

Conclusion
Machine learning and data science are an art and it is not an easy work to identify which features are correlated in a new dataset. However, it's interesting to see the differences in the clustering using K-Means and PCA, as this last method decreases the spread between the datapoints, offering a better visualization on which points belong to which cluster. 

The files used in this challenge are available in the GitHub's repository on https://github.com/PrisBriggs/CryptoClustering.git .

The references used in this Challenge were the activities and lessons given in class, the tutoring classes, and the websites below. 

All webpages were visited in May/2023.

References:

https://holoviz.org/tutorial/Composing_Plots.html
https://www.youtube.com/watch?v=FgakZw6K1QQ (StatQuest: Principal Component Analysis (PCA), Step-by-Step)
https://stackoverflow.com/questions/1995615/how-can-i-format-a-decimal-to-always-show-2-decimal-places
https://hvplot.holoviz.org/user_guide/Customization.html
https://towardsdatascience.com/dealing-with-highly-dimensional-data-using-principal-component-analysis-pca-fea1ca817fe6#:~:text=The%20explained%20variance%20ratio%20is,or%2080%25%20to%20avoid%20overfitting.


