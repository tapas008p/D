# Dimensional reduction using PCA and t-SNE

## Principal component analysis
PCA is an unsupervised linear dimensionality reduction and data visualization technique for very high dimensional data. As having high dimensional data is very hard to gain insights from adding to that, it is very computationally intensive. The main idea behind this technique is to reduce the dimensionality of data that is highly correlated by transforming the original set of vectors to a new set which is known as Principal component. PCA tries to preserve the Global Structure of data i.e when converting d-dimensional data to d’-dimensional data then it tries to map all the clusters as a whole due to which local structures might get lost. Application of this technique includes Noise filtering, feature extractions, stock market predictions, and gene data analysis.

## t-SNE (t-distributed stochastic neighbourhood embedding)
 t-SNE is also a unsupervised non-linear dimensionality reduction and data visualization technique. The math behind t-SNE is quite complex but the idea is simple. It embeds the points from a higher dimension to a lower dimension trying to preserve the neighborhood of that point.

Unlike PCA it tries to preserve the Local structure of data by minimizing the Kullback–Leibler divergence (KL divergence) between the two distributions with respect to the locations of the points in the map. This technique finds application in computer security research, music analysis, cancer research, bioinformatics, and biomedical signal processing.
 
## Difference between PCA and t-SNE
|S.no | PCA    | t-SNE   |
|:---: | :---: | :---: |
| 1 |It is a linear Dimensionality reduction technique. |	It is a non-linear Dimensionality reduction technique.  |
| 2 |It tries to preserve the global structure of the data.. |	It tries to preserve the global structure of the data.  |
| 3 |It does not involve Hyperparameters. |	It involves Hyperparameters such as perplexity, learning rate and number of steps.  |
| 4 |It gets highly affected by outliers. |	It can handle outliers.  |
| 5 |It works by rotating the vectors for preserving variance. |	It works by minimising the distance between the point in a gaussian.  |


[Dataset : https://www.kaggle.com/competitions/digit-recognizer/data?select=train.csv ](https://www.kaggle.com/competitions/digit-recognizer/data?select=train.csv)
