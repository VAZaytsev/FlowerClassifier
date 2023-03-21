# Flower classifier

We construct the flower classifier on the basis of the [dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/), consisting of 102 flower classes. In each class, there are from 40 to 258 images. To convert each image into a feature vector we will use a pre-trained convolutional neural network ResNet-50, which was first presented in this [preprint](https://arxiv.org/abs/1512.03385) and currently can be found in many machine learning frameworks. Here we will use TensorFlow.

Similar projects can be found [here](https://towardsdatascience.com/build-train-and-deploy-a-real-world-flower-classifier-of-102-flower-types-a90f66d2092a) and [here](https://www.kaggle.com/code/dtosidis/flower-classifier-tensorflow/notebook). 

Everything can be found in the [ResNet.ipynb](ResNet.ipynb) file
