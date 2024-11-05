# CryptoClustering
Module_19_Challenge_Unsupervised_Learning

### For this assingment I am working on a project to explore patterns in cryptocurrency prices, looking specifically at how they change over 24 hours and 7 days.

I started by loading the data, scaling it so everything’s on the same level, and then used the elbow method to figure out the ideal number of groups (or clusters) for these cryptocurrencies. 
Once I had a good cluster number, I used K-means clustering to actually group them and then visualize these groups to see if there are any interesting patterns in the short and medium term price changes.
After that, I tried simplifying the data by reducing it to three main features using PCA. I repeated the clustering steps to see if this simplified version gives similar or different results. 
By the end, I had a good sense of whether fewer features can still reveal meaningful patterns, or if more detail is necessary to capture how these cryptocurrencies behave.