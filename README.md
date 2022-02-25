# Fashion-recommender

A Recommender System that takes a image as input  then find five visually simliar images from the database and generate recommendition.It is built using **KNN(K nearest neighbours
a Machine learning algorithm)** and **ResNet (Deep Learning CNN architecture)** is used for feature extraction from the images.it works on the concept of **Reverse image search**

From Wikipedia,**Reverse Image Search** is a content-based image retrieval query technique that involves providing CBIR system with a sample image that it will then base its search
upon.Reverse image search also allows users to discover content that is related to a specific sample image, popularity of an image, and discover manipulated versions and 
derivative works

**Dataset used for this recommender :** https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset

### KNN(k nearest neighbours):
The K-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. 

The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.K-NN algorithm assumes the similarity between the 
new case/data and available cases and put the new case into the category that is most similar to the available categories.

It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, 
it performs an action on the dataset.

![image](https://user-images.githubusercontent.com/55338522/155275648-0a3c8b15-9f9e-4827-aa4e-d06a673fbc39.png)

### Feature extraction using ResNet:

![image](https://user-images.githubusercontent.com/55338522/155275881-697d64a1-7a5d-4522-9225-e0e57c2a5e9e.png)

## Demo-
![Screenshot (114)](https://user-images.githubusercontent.com/55338522/155276225-233d9821-92bd-4041-b6cf-53ce07e925fe.png)

![Screenshot (115)](https://user-images.githubusercontent.com/55338522/155276257-13fdd7f2-3bf5-49cc-8332-4fc8e54393ae.png)







