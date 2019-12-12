# Optimal-K-selection-in-KMeans
Test of multiple criterias to choose the optimal K value in Kmeans clustering to classify a dataset

We want to see the best criteria to classify datasets between inertia, silhouette and a criteria that has been created in this document : PhamDN-kmeans.pdf written by D T Pham, S S Dimov, and C D Nguyen.

Firstly we use the iris's dataset where we already know the number of class (4) and we want to know the number of class that the kmean method will give with different values of k and select the optimal K value (the K value that give the appropriate number of classes.

After that we generate 100 iterations of three classes, each class containing 50 2D-points generated randomly with a Gaussian law with specified parameters (mu,Sigma) and use the criterias to estimate the number of classes.

At the end we plot the results and interpret.
