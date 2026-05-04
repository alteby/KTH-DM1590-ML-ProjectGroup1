# KTH-DM1590-ML-ProjectGroup1
Develop a machine learning system that can distinguish which animal is being shown in a picture.  
We will extract features using a combination of HOG (to capture shapes and edges) and LBP (to detect texture such as fur) as well as using RGB pixel values to distinguish colour information. These features will be concatenated to a vector that represents each image. 

We will use supervised learning and train a kNN-model to classify and find patterns in the feature vectors by dividing them into a testing and training set. We will also use unsupervised learning, PCA for dimensionality reduction and visualization and k-means clustering. We are using a labeled dataset with animal images from Kaggle. Each image belongs to an animal class. 

Dataset: https://www.kaggle.com/datasets/alessiocorrado99/animals10/data
