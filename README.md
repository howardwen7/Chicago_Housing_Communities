# Chicago Housing Communities Clustering

## Project Background and goals
Housing communities that together constitute a large metropolitan area exhibit different characteristics. I took Chicago as an example and examined whether certain places may be more similar than others. In other words, I want to see whether there exists any meaningful grouping of housing communities. Even if there is not an obvious cluster, it would be helpful to identify one or two places that may be distinct from the rest. 

## Data Description
The dataset consists of 78 housing communities that constitute the Chicago metro area. Each of the six features is a socioeconomic-related characteristic. There is no target variable. 

## Methodology
I utilized principal component analysis and projected all data points to the first two principal components. After the projection, I visualized the scatter plot of the two PCs to see whether any obvious clusters can be identified. Since there might be some nonlinear relationships in the dataset, I also attempted kernel PCA to identify the same or additional groups of cluster(s). Loadings of each feature for the two PCs were also examined to see whether certain features are associated. 

## Exploratory Results
When using just the basic PCA, I identified six places that are geographically close to each other and of overall better socioeconomic characteristics. However, once I used KPCA with the polynomial kernel, I identified two additional places that might constitute another group. As PCA/KPCA is an unsupervised learning technique, no concrete statements can be drawn. However, future investigations can explore these two groups of communities through a deep dive into how they are similar within each group and different between each group and how they might be distinct from all others. 
