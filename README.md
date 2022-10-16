# Chicago Housing Communities

## Project Background and goals
Housing communities that together constitutes a large metropolitan area exhibit different characteristics. I took Chicago for example and examined whether certain communities may be more similar than others. In other words, I want to see whether certain clusters of housing communities can be identified. Even if there is not an obvious cluster, it would be helpful to identify one or two housing commmunities that may be distinct from the rest of places. 

## Data Description
The dataset consists of 78 housing communities that constitutes the Chicago metro area. Each of the six features is a socioeconomic-related characteristics on that housing community. There is no target variable. 

## Methodology
I utilized principal component analysis and projected all data points to the first two principal components. After the projection, I visualized the scatter plot of the two PCs to see whether any obvious clusters can be identified. Since there might be some nonlinear relationships in the dataset, I also attempted kernel PCA to identify the same or additional groups of cluster(s).

## Exploratory Results
When using just the basic PCA, I was wable to eyeballed six communities that are geographically close to each other and of overall better socioeconomic characteristics. However, once I used KPCA with the polynomial kernel, I identified two additional communities that might constitute another group. As PCA/KPCA is an unsupervised learning technique, no concrete statements can be drawn. However, future investigations can explore these two groups of communities first, by doing a deep dive into how they are similar within each group and different between each group ansd how they might be distinct from the rest. 
