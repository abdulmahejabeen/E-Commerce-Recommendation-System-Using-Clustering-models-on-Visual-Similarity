## Visual Similarity-Based Clothing images Recommendation System
### Objective
This project aims to improve e-commerce recommendation systems using the machine learning techniques for fashion product recommendations to a dataset containing over 5000 high-definition clothing images. 

### Methodology
<img width="600" alt="image" src="https://github.com/abdulmahejabeen/E-Commerce-Recommendation-System-Using-Clustering-models-on-Visual-Similarity/assets/56336879/1046a501-ebb3-457c-b261-39c3ee57fa5e">

The steps performed in this project are Data collection, Preprocessing, Dimensionality reduction techniques, followed by Modelling using Clustering methods. This project uses (CRISP-DM) approach. 

### Dataset Description
- Datasource link: [Clothing dataset](https://www.kaggle.com/datasets/agrigorev/clothing-dataset-full)
- Over 5,000 images of 20 different classes and were around 7.07 GB.
- These were crowdsourced rom social networks and collaboration platforms Toloka and Tagios.

### Data Preprocessing
- Check for incomplete image data and remove them.
- Check for any incorrect format or corrupt images using PIL and discard them.
- Normalization techniques inconsistent resolution of images to rescale or normalize them to a uniform size.
- Data Augmentation techniques includes Image Flipping and Image Rotation

### Dimensionality Reduction
- Principal component analysis (PCA) is used with Singularity Value Decomposition (SVD) on the high-dimensional dataset.
- It is used for image compression and is regarded as the most effective tool for data reduction and had achieved a compression image size of 66.72% of the original image.

### Modelling
Unsupervised Machine learning models- Clustering algorithms are used such as K-means++, Minibatch, Birch, and Agglomerative.

### Evaluation metrics 
This research utilizes the most efficient and common cluster performance evaluation metrics: 
- Silhouette score
- Calinski-Harabasz index and
- Davies-Bouldin Index.

### Results
<img width="652" alt="Screenshot 2024-02-08 at 6 03 02 PM" src="https://github.com/abdulmahejabeen/E-Commerce-Recommendation-System-Using-Clustering-models-on-Visual-Similarity/assets/56336879/1183e57c-fac2-4574-b4ef-54d03718cf92">

- Birch Model achieves a Silhouette score of 0.67 and Davies-Bouldin Index score of 0.32 at the 5 optimal number of clusters. 

