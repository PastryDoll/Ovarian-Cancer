# Ovarian-Cancer

In this notebook we will analize the Ovarian Cancer Dataset. This is a dataset, that come with MATLAB, consists of a 216x4000 matrix of 216 patients (rows), and 4000 (columns) indicating genetic markers measured on each patient. We also have an array that indicates if the patient have ovarian cancer or not.

Our objective is to perform a PCA on this matrix, and extract from it its 3 principal components. After performing the PCA, we will plot the transformed data point, and investigate if they seen to divide into clusters, this will tell us if it is natural to ask for a classification model to fit our data.

We obtained a recall score of 1. 

![PCA](https://user-images.githubusercontent.com/110412014/208276487-c2d9d178-e000-4edf-9c70-4ef1cf9f9e39.png)

![3DPCAscat](https://user-images.githubusercontent.com/110412014/208276480-30f85f51-3789-4df8-b76d-1feb67ed3c03.png)

Confusion Matrix for Test Set:

![confusion](https://user-images.githubusercontent.com/110412014/208276485-f01c73cc-b33a-4064-8dac-e69db52e3e4b.png)

![2d](https://user-images.githubusercontent.com/110412014/208276298-a43b49cd-bcc7-43f5-b5d0-7c57230b6a94.png)

![3d](https://user-images.githubusercontent.com/110412014/208276299-2b0b88b6-49b5-4540-b98f-1ca1cb1d51cb.png)
