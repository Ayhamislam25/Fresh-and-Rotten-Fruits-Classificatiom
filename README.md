# Fresh-and-Rotten-Fruits-Classificatiom
Classification for Fresh and Rotten fruits using cnn and imagenet pretrained model with accuracy 97%
Fresh and Rotten Fruits Classification Using CNN
This repository contains a classification model using Convolutional Neural Network (CNN) with pre-trained ImageNet to classify fresh and rotten fruits dataset. The dataset contains 67,939 photos of fresh and rotten apples, bananas, and oranges.

Dataset
The dataset is divided into six classes:

Fresh Apples
Fresh Bananas
Fresh Oranges
Rotten Apples
Rotten Bananas
Rotten Oranges
The dataset is available for download from Kaggle.

Model
The model uses a pre-trained CNN with ImageNet weights to extract features from the input fruit images. Softmax is used to classify the images into fresh and rotten fruits.

The performance of the proposed model is evaluated on the dataset and produces an accuracy of 97.82%.

Requirements
The following packages are required to run the code:

Python 3.x
NumPy
TensorFlow
Keras
Usage
To train the model, run the following command:

python train.py

To test the model, run the following command:

python test.py

Results
The proposed CNN model can effectively classify the fresh fruits and rotten fruits. The accuracy of the model is 97.82%.

Conclusion
The proposed model can be used to identify the defects in the fruits in the agricultural industry. The model can reduce human efforts, reduce the cost and time for production by identifying the defects in the fruits. The model can also avoid the spread of rottenness.
