# Facial Image Classification with Tensorflow pre-trained model

The goal of this project is to use TensorFlow to build an efficient Face Recognition model which can be used to detect faces with OpenCV and front face detector xml. We firstly cut and resize faces to improve the training performance of the model then we normalize the data in the range [0,1]. Second we use a pre-trained model in TensorFlow to build our model, and then finally use our model to classify the photos.

In order to run fster the code we use GPU mode, which can be achieved as: click open a Google Colab notebook, click 'Runtime', then 'Change Runtime', choose GPU and then click 'Save'. 
