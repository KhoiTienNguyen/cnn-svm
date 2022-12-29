An Architecture Combining Convolutional Neural Network (CNN) and Linear Support Vector Machine (SVM) for Image Classification
===

In this project, we were tasked to reproduce a scientific paper. We chose Abien Fred Agarap’s paper in which
the main topics are Convolutional Neural Networks with Support Vector Machines in order to classify images in
Fashion-MNIST and MNIST datasets. We compared the performance of this model with a CNN softmax model in
order to see if an output SVM layer increases or decreases the test accuracy when classifying images in the datasets.
We experimented with different hyper-parameters as well as parameters to see which model performed the best. We
found that the CNN model with softmax output layer results in test accuracy of 99.32% and 91.88% for MNIST and
Fashion-MNIST datasets respectively. On the other hand, the CNN model with a SVM output layer results in test
accuracy of 99.17% and 91.75% for MNIST and Fashion-MNIST datasets respectively.

Authors: Chloe Mills, Shania Wan-Bok-Nale, Khoi Nguyen
Original Code's Author: Abien Fred Agarap