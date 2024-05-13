# CIFAR10-PyTorch

## CIFAR10 CNN implementation using PyTorch

Blog post to this project can be found [here](https://machinelearningbrain.website/pytorch-cnn-on-cifar10/)

Trained a Convolutional Neural Network model(CNN) to perform Multi-Class Image Classification. The model defines four convolutional layers to extract features from input images and max-pooling layers to reduce the spatial size of the resulting feature map. The output from the convolutional layers is then passed through fully connected layers for classification, with dropout applied for regularization. It's been trained on CIFAR-10 dataset for 20 epochs on a GPU. It achieved a testing accuracy of 68.08% on a testing dataset of 10,000 images.

### Dataset

The CIFAR-10 (Canadian Institute for Advanced Research, 10 classes) dataset has a total of 60,000 images split into 50,000 training images and 10,000 test images. Each image is of size 32 x 32 x 3 (32 wide, 32 high, 3 color channels). Each pixel-channel value is an integer between 0 and 255. Each image is one of 10 classes: plane (class 0), car, bird, cat, deer, dog, frog, horse, ship, truck (class 9). Most deep learning frameworks, including PyTorch, Tensorflow, and Keras, have built-in CIFAR-10 datasets.

### Files

* [mean_std.ipynb](mean_std.ipynb): In this file, I calculated the mean and standard deviation of the dataset.
* [CNN_CIFAR10.ipynb](CNN_CIFAR10.ipynb): Checking the images, defining and training the CNN model, and testing the model.
