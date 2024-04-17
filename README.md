# CryptoClustering
module 19
Data Loading and Initial Exploration: The process began by importing the data into a Pandas DataFrame and examining the initial statistics and plots.

Data Normalization: The StandardScaler from scikit-learn was employed to normalize the data.

K-Means Clustering: K-Means clustering was conducted, which included determining the optimal number of clusters (k) using the Elbow method, training the K-Means model, and predicting clusters.

Principal Component Analysis (PCA): PCA was implemented to reduce the dataset to three principal components and explore the explained variance.

Clustering on PCA-Transformed Data: The K-Means clustering procedure was repeated on the data after PCA transformation, evaluating the effects of using reduced features for clustering.

Visualization and Analysis: Various visualizations, such as Elbow curves and scatter plots, were generated to display and assess the clustering outcomes. The interpretation of these plots and the significance of the results observed were also explained.

Comparative Analysis: The clustering outcomes between the original and PCA-reduced datasets were contrasted. This included an assessment of the clarity of clusters, computational efficiency, and ease of interpretation.

Explained Variance: The importance of the total explained variance by the principal components in the PCA was calculated and elaborated on.

Impact of PCA on Clustering: The consequences of utilizing fewer features (through PCA) on K-Means clustering were discussed, focusing on aspects like cluster quality, interpretability, and the trade-off between overfitting and underfitting.

Credits
Resources such as Google, ChatGPT, and Stack Overflow were utilized for this project.
