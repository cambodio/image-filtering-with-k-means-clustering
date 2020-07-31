# Imagine Color Filtering using k-means Clustering Algorithm

(**Project 1 for CSCI1913**) This project aimed to have to student write a k-means clustering algorithm and to implement the algorithm by doing image color filtering.

## The Project

### k-means Clustering Algorithm
Given a *k* amount of clusters and a set of data, seperate the set of data into whichever *k* cluster the data point is closest to. 

The starting value of each *k* cluster is determined randomly. Once the first cycle of categorizing data points into their respective clusters is complete, the value of each *k* cluster is re-evaluated to the average value of all the data points belonging to that cluster. The cycle of categorizing data points and re-evaluating *k* cluster values is repeated until the value of the clusters do not change. Once the values of *k* clusters stop changing, then you have your *k* clusters containing their closet representing data points.

### Image Filtering using k-means Clustering
Image color filtering is implemented by having *k* re