# CIFAR-10

This project demonstrates the use of deep learning techniques to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes. In this project, a Convolutional Neural Network (CNN) was built and trained to classify these images into their respective categories with a high degree of accuracy.

## Problem Statement

Image classification is a crucial task in computer vision with numerous applications ranging from autonomous driving to medical image analysis. The goal of this project was to develop a model that could accurately classify images from the CIFAR-10 dataset into one of 10 predefined categories, such as airplanes, automobiles, birds, cats, etc.

## Machine Learning Approach

### Data Preprocessing
The images were normalized to have pixel values between 0 and 1 to improve the efficiency of the model training process.

### Model Architecture
A Convolutional Neural Network (CNN) was used for this task due to its ability to capture spatial hierarchies in the data. The architecture includes:
- For feature extraction from images.
- For downsampling and reducing the dimensionality of the feature maps.
- For mapping the features to the output classes.
- For generating probabilities for each class.

### Training
The model was trained for 10 epochs using the Adam optimizer and sparse categorical cross-entropy loss function. During training, the model's performance was validated using a separate test set.
