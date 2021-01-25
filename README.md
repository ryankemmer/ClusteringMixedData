# Clustering Mixed Data 

Many datasets contain a mixture of categorical and continuous data. However, it is not straightforward how to cluster datasets with mixed data types. This repository contains a notebook that takes a look at two simple ways to approach this problem using Python.

Read the full medium article, here!

https://ryankemmer.medium.com/clustering-on-mixed-data-types-in-python-7c22b3898086

### Dataset

In this repo, I am cluster a small dataset I created that has a mixture of categorical and continuous features. My fake data represents customer data that might be used to understand customers of an E-commerce website/app. Our fake dataset will have 4 features:

OS — operating system of our fake customer (Categorical)
ISP — internet service provider of our fake customer (Categorical)
Age — customer age (Continuous)
Time Spent — time that our fake users spent on our website (Continuous)

### Method 1: K-Prototypes

The first clustering method we will try is called K-Prototypes. This algorithm is essentially a cross between the K-means algorithm and the K-modes algorithm.

### Method 2: K-Means with One Hot Encoding

An alternative to using the K-prototypes algorithm is using the K-means algorithm and one hot encoding categorical variables.

### Conclusion

Using our fake dataset, there are significant differences in the clusters determined by these two methods. K-prototypes seemed to evenly consider categorical and continuous features. Meanwhile, K-means seemed to weigh categorical features MUCH more heavily, which would likely be undesirable.





