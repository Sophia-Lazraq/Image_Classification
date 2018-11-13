# Image_Classification
This is the data challenge for the course Kernel Methods for Machine Learning of the MVA program : 
https://www.kaggle.com/c/kernel-methods-for-machine-learning-data-challenge
We need to implement kernel method ourselves instead of using existing libraries, e.g. sklearn.
Team on the learderboard: SLOC

## Image Classification with Kernels
### Team members: Peter Martigny, Sophia Lazraq, Olivier Chancé
The goal of this project is to classify images from CIFAR dataset, which consists of 10 different classes: airplane, dog, cat, car, horse, frog, truck, bird, deer, ship.

The constraint of this project is: DO IT YOURSELF! which means no access to machine learning libraries (keras, sklearn, opencv...)

## Methodology
### Fetures creation with SIFT
Build a SIFT features extractor

### Chi2 Kernel
Build a Chi2 Kernel to embed the features

### SVM
Build a Support Vector Machine (SVM) to classify images, with a one-versus-all method to go multi-class

### Additional Trick: Data Augmentation
Flip the images to double the size of the training set

### Results
The metrics of concern is the accuracy On the prvate leaderaboard, our model without data augmentation produces an accuracy of 63.5%. With data augmentation, the model lead to an accuracy of 65.5%
