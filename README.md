# Face Mask Detection for COVID-19

## Goal

Implemented during the COVID-19 pandemic, this project aimed to gain a deeper understanding of Computer Vision, while focussing on its utilization, contributing a practical solution while exploring new technologies.


## Tech Stack

### Languages & Libraries
- Python, Numpy, Pandas, OpenCV, Keras, Tensorflow, Scikit-Learn, imutils, Jupyter Notebook

### Models Used
- MobileNetV2

## Dataset

The dataset comprised mask and no mask human images obtained from Kaggle. It facilitated training the neural network for face mask detection.

## Project

- Utilized a Deep Learning MobileNetV2 model alongside OpenCV and Keras to achieve 99% accuracy in predicting ‘mask’ and ‘no mask’ categories.
- Programmed the neural network model using MobileNetV2 as a replacement for the Convolution Layer, incorporating Pooling layers, and other necessary adjustments.
- Trained and cross-validated the model on train and test data, visualizing accuracy, precision, recall, and loss metrics.
- Once the model demonstrated strong performance, integrated it into mask detection leveraging existing code for face detection using OpenCV's DNN functions.
- Model testing involved leveraging imutils VideoStream, displaying live video analysis to ascertain accurate mask placement percentages.
- Model testing involved leveraging imutils VideoStream, displaying live video analysis to ascertain accurate mask placement percentages. 

## Learning
- Gained a deeper understanding of CNNs and MobileNet as a CNN architecture by programming the neural network model with MobileNetV2 and cross-validating the model on train and test data.
- Visualization accuracy, precision, recall, and loss to aided in simplifying the understanding of the project.
