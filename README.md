# Adversarial MNIST Image Generation

We generate adversarial "6" digit images from real "2" digit images. A sample of adversarial "6" digit images, along with their corresponding "2" digit images, and their differences are provided [here](https://github.com/rhseqlhs/adversarial_MNIST/blob/master/Image_Table.png).

We conclude with two possible ways to find adversarial images: using Dropout at test time and using one class SVMs.

We include saved files of the trained ConvNet, as well as pickled datasets for our one class SVMs. Thus, running the segments on training and data generation are optional, and are marked as such.

The ConvNet we use is precisely the ConvNet code provided at the TensorFlow tutorial website [here](https://www.tensorflow.org/get_started/mnist/pros).

A brief analysis of the contents of the notebook is provided [here](https://github.com/rhseqlhs/adversarial_MNIST/blob/master/Adversarial_MNIST_Analysis.pdf).

## Requirements
To run the notebook, we will need
```
Python 2.7
NumPy
SciPy
Matplotlib
TensorFlow
scikit-learn
```
The last requirement on scikit-learn is only necessary for running the final 2 segments.
