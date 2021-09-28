# Classification of Clothing images using Keras in R

Fashion_MNIST data set is directly available from keras package in R. 

This dataset contains 70,000 grayscale images in 10 categories. In this project, 60,000 images are used to train the network and 10,000 images are used for testing the model’s performance. Individual images contain low-resolution (28 x 28 pixels) articles of clothing. Each image is a 28x28 array, with pixel values ranging between 0 and 255. The labels are arrays of integers, between 0 and 9.

The neural network is trained using 10 epochs, with a batch size of 256. The accuracy of the model is evaluated and first five observations are predicted for the test data.
