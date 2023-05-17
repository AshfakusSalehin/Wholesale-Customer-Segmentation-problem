<!-- Wholesale Customer Segmentation 

Problem Statement
The aim of this problem is to segment the clients of a wholesale distributor based on their annual spending on diverse product categories, like milk, grocery, region, etc.

 Download Dataset from Here: wholesale.csv

 Dataset Description:

The data set refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories.

Attribute Information:

1) FRESH: annual spending (m.u.) on fresh products (Continuous);
2) MILK: annual spending (m.u.) on milk products (Continuous);
3) GROCERY: annual spending (m.u.)on grocery products (Continuous);
4) FROZEN: annual spending (m.u.)on frozen products (Continuous)
5) DETERGENTS_PAPER: annual spending (m.u.) on detergents and paper products (Continuous)
6) DELICATESSEN: annual spending (m.u.)on and delicatessen products (Continuous);
7) CHANNEL: customersâ€™ Channel - Horeca (Hotel/Restaurant/CafÃ©) or Retail channel (Nominal)
8) REGION: customersâ€™ Region â€“ Lisnon, Oporto or Other (Nominal)

There are multiple product categories – Fresh, Milk, Grocery, etc. The values represent the number of units purchased by each client for each product. The goal of this project is to make clusters from this data that can segment similar clients together. You will, of course, use Hierarchical Clustering for this problem. Let’s explore the data first and then apply Hierarchical Clustering to segment the clients using Spark Machine Learning (Spark MLlib) with PySpark.
.

Steps to solve the problem:
1.       Import a dataset and needed libraries

2.       Data Exploration

In this section, you will begin exploring the data through visualizations and code to understand how each feature is related to the others. You will observe a statistical description of the dataset, consider the relevance of each feature, and select a few sample data points from the dataset which you will track through the course of this project.

3. Clustering using Hierarchical Method.

4.  Choose the optimal number of clusters.

5. Fit our model and make predictions. -->
