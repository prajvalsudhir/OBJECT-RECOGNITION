# OBJECT-RECOGNITION
Convolutional neural netwok to recognise various objects in the CIFAR-10 dataset

## The CIFAR-10 dataset

Homepage: https://www.cs.toronto.edu/~kriz/cifar.html

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.


The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


Here are the classes in the dataset, as well as 10 random images from each:							
              
![spot Logo](https://miro.medium.com/max/964/1*syyml8q8s1Yt-iEea5m1Ag.png)

* The Model has been trained using Keras and Tensorflow 2.0 frameworks

* The images have been normalised and scaled for training.

* The lables have been converted to categorical values(one-hot encoding) for multi-class classification

* The model has shown a training accuracy of 73% and validation accuracy of 67% on training for 6 epochs
