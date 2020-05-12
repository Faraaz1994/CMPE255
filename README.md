# CMPE255
Facial Emotion Recognition

This is a [Kaggle challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). The dataset consists of 48x48 grayscale images of faces. All the faces are centrally aligned and occupy around the same amount of space. The objective of this project is to recognise the emotion depicted by the human in the image.

We have built multiple models using Convolutional Neural Networks, Support Vector Machines, Recurrent Neural Networks, Decision trees and K-Nearest Neighbours. The notebooks are present in the src folder.
Dataset can be found in [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). 

# Steps to run

#### Follow the folder Structure
    ├── src
    |    └── notebook.ipynb
    └── Data
         └──  fer2013.csv
    
* Download the dataset from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* Download the notebook of interest from [here](https://github.com/Faraaz1994/CMPE255/tree/master/src)
* The commands to install the dependencies are provided in each notebook. Run the commands to install the necessary dependecies
* Assign the path to the src folder to the variable 'directory' present in the notebooks
* Run the notebook

# Preprocessing techniques:
* [Min-max Normalization](https://github.com/Faraaz1994/CMPE255/blob/master/src/CNN/CMPE255_Normalization.ipynb)
* [Principal Component Analysis](https://github.com/Faraaz1994/CMPE255/blob/master/src/SVM/CMPE255_SVM_100_PCA.ipynb)
* [L2 Normalization](https://github.com/Faraaz1994/CMPE255/blob/master/src/KNN/CMPE255_KNN.ipynb)

# Feature Engineering techniques:
* [Bag of Visual words](https://github.com/Faraaz1994/CMPE255/blob/master/src/SVM/CMPE255_SVM_100.ipynb)
* [Vector of Locally Aggregated Descriptors](https://github.com/Faraaz1994/CMPE255/blob/master/src/KNN/CMPE255_KNN.ipynb)

# Algorithms Used:
* Convolutional Neural Networks
* Support Vector Machines
* Recurrent Neural Networks
* Decision tree
* K-Nearest Neighbours
* Logistic Regression

# Top five accuracies in the Kaggle [leaderboard](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/leaderboard)
* 71.16%
* 69.26%
* 68.82%
* 67.48%
* 65.25%


# Accuracies achieved by us:
| Algorithm                                       | Accuracy |
|-------------------------------------------------|----------|
| [Convolution Neural Networks(Data augmentation)](https://github.com/Faraaz1994/CMPE255/blob/master/src/CNN/CMPE255_Augmentation.ipynb)  | 64.35%   |
| Convolution Neural Networks                     | 55.84%   |
| Recurrent Neural Networks                       | 38.35%   |
| Logistic Regression                             | 38.49%   |
| KNN                                             | 35.52%   |
| Support Vector Machine                          | 33.18%   |
| Decision Tree                                   | 25.09%   |



