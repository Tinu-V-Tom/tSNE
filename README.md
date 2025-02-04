# Comparison of t-SNE and PCA
This is an attempt to mark the difference between PCA and tSNE . 
They differ by the following means.

Type:

t-SNE: Non-linear dimensionality reduction.
PCA: Linear dimensionality reduction.
Goal:

t-SNE: Preserves local pairwise similarities.
PCA: Preserves global variance.
Best Use Cases:

t-SNE: Visualizing complex, high-dimensional data (e.g., NLP, image datasets).
PCA: Handling data with linear structure, feature extraction, and noise reduction.
Output:

t-SNE: Low-dimensional representation emphasizing local relationships.
PCA: Principal components that explain global variance in the data.
Computational Intensity:

t-SNE: Computationally expensive and suitable for smaller datasets.
PCA: Computationally efficient and scalable to large datasets.
Interpretation:

t-SNE: Harder to interpret due to its stochastic and non-linear nature.
PCA: Easier to interpret as it provides measurable variance for each component.
