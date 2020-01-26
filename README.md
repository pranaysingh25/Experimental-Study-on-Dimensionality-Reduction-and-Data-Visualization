# Experimental-Study-on-Dimensionality-Reduction-and-Data-Visualization

The project was based on Dimensionality Reduction Algorithms in which I used Various Compression methods to find the answers to the following questions:

1. Dimensionality Reduction for performance: Does PCA always help? Does it improve training time and performance accuracy?
>> I found that PCA helps, but not always. In fact, Dimensionality Reduction does not always lead to faster training, it rather depends on the dataset, the model and the training algorithm used.

2. Dimensionality Reduction for Visualization: What are different Dimensionality Reduction methods for visualization and how better or worse are they in terms of speed and visualization.
>> TSNE out-performed other algorithms at making clear clusters.
>> PCA, when chained with other algorithms, helps to perform reduction faster.
>> PCA scales faster than other algorithms but is not that good in creating clusters.
>> Manifold based algorithms scale very poorly with larger datasets, hence they are very slow.
