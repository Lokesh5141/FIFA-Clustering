# FIFA Clustering
An end-to-end machine learning project that preprocesses and clusters FIFA player data to uncover patterns in performance attributes. This repository includes data cleaning, dimensionality reduction (PCA, t-SNE), clustering (K-Means, Hierarchical Clustering), and visualization techniques to reveal distinct groups of players.

# Project Details
 ## Data Preprocessing
- Data Cleaning: Handled missing values using SimpleImputer, KNNImputer, and IterativeImputer.
- Scaling: Standardized the features with StandardScaler.
- Dimensionality Reduction: Employed PCA to reduce the feature space and t-SNE for visualization.

## Clustering
- K-Means Clustering: Implemented with scikit-learn along with the KElbowVisualizer from Yellowbrick to determine the optimal number of clusters.
- Hierarchical Clustering: Used scipy.cluster.hierarchy to perform hierarchical clustering and generate dendrograms.
- Performance Metrics: Evaluated cluster quality using silhouette scores.

## Visualization
Visualizations were created using Matplotlib, Seaborn, and Plotly to provide both static and interactive insights into the clustering results.
Results

The project successfully segments FIFA players into distinct clusters based on their performance attributes.
Key visualizations include cluster scatter plots, dendrograms, and interactive Plotly charts.
Insights derived from the clusters can be used to better understand player characteristics and potential market segmentation.

## Dependencies
The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- Pillow
- plotly
- yellowbrick

### These are all listed in the requirements.txt file. Install them using:
pip install -r requirements.txt

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Acknowledgements
Thanks to the community for providing open-source datasets and libraries.
Special thanks to [FIFA] for making the player dataset available (if applicable).


---

Feel free to modify any section as needed based on the specifics of your implementation or project requirements. When you share your notebook file, we can further tailor sections like “Project Details” and “Results” to match your actual experiments and outcomes.

