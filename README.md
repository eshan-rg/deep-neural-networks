# Deep-Neural-Networks-Model-Keras-Tensorflow-
Understood the basics of the deep neural networks. Build the DNN models FCNN, CNN and RESENT50 in keras & tensorflow. Tested the models built on the following datasets:

1. From keras.datasets imported MNIST dataset which contains images of handwritten digits and has a training set of 60,000 examples, and a test set of 10,000 examples. A three dense layered Fully Connected Neural Network model was build and the model was tested by this dataset from scratch.

2. From keras.datasets imported CIFAR-10 dataset which contains colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test         images. A Convolutional Neural Networks model comrising of three convolutional layers and two dense layers was built and the CIFAR-10 dataset was tested on this model from scratch.

3. Locally imported the Hand-sign Dataset in .h5 format using the h5py package. There are a total 1080 images in the train data and 120 images in the test data, each of which is a 3 channel image of dimension 64x64. A deep learning neural network, ResNet-50 was made to recognize numeric signs using our hand and the model was tested on the above mentioned dataset from scratch.


# Bubble-Sort-Algorithm-in-Python
Bubblesort is an elementary sorting algorithm. The idea is to
imagine bubbling the smallest elements of a (vertical) array to the
top; then bubble the next smallest; then so on until the entire
array is sorted.

Example: <br />
First Pass:  
( 5 1 4 2 8 ) –> ( 1 5 4 2 8 ), Here, algorithm compares the first two elements, and swaps since 5 > 1. \
( 1 5 4 2 8 ) –>  ( 1 4 5 2 8 ), Swap since 5 > 4 \
( 1 4 5 2 8 ) –>  ( 1 4 2 5 8 ), Swap since 5 > 2 \
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ), Now, since these elements are already in order (8 > 5), algorithm does not swap them.\
Second Pass: \
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ) \
( 1 4 2 5 8 ) –> ( 1 2 4 5 8 ), Swap since 4 > 2 \
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) \
( 1 2 4 5 8 ) –>  ( 1 2 4 5 8 ) \
Now, the array is already sorted, but our algorithm does not know if it is completed. The algorithm needs one whole pass without any swap to know it is sorted. \
Third Pass: \
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) \
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) \
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) \
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) \
