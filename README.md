# Unsupervised-machine-learning-challenge
This activity is broken down into four parts:

Part 1: Prepare the Data.

Part 2: Apply Dimensionality Reduction.

Part 3: Perform a Cluster Analysis with K-means.

Part 4: Make a Recommendation.

Working process:
Part 1: Prepare the Data
1.Read myopia.csv into a Pandas DataFrame.
2.Remove the "MYOPIC" column from the dataset.
3.Standardize the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.
Part 2: Apply Dimensionality Reduction
1.Perform dimensionality reduction with PCA. How did the number of the features change?
The number of features have been changed ,reduced to 12 from 14.
2.Further reduce the dataset dimensions with t-SNE and visually inspect the results.
 To do this, run t-SNE on the principal components, which is the output of the PCA transformation.
3.Create a scatter plot of the t-SNE output. Are there distinct clusters? 
