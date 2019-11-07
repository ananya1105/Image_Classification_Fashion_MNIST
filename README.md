# Image_Classification_Fashion_MNIST
This project involves classification of images using Convolutional Neural Architecture(CNN) using the keras framework of python.
The data can be accessed from keras datasets. 
Here, I am using keras training it on tensorflow. Keras is deep learning library of python that is used for advanced prototyping.
Three key advantages of keras :
1. It is user friendly
2. It is modular and easy to extend

I have used Fashion MNIST dataset(it contains 70,000 grayscale images and seven categories)
Images show the articles of clothing at low resoulution that is 28X28 pixels.
I have used 60,000 images to train the network and rest 10,000 images to test.
As labels we have T-shirts, pullovers, trousers dress coat sandal shoes
Then I explored the data.
Here I have chained together simple layers
Flatten layer is used to convert a 2-D array to 1-D array  of dimension 784(28x28)
In the last layer I have used softmax funciton
We get the output as probablity scores.
I have used adam optimizer and categorical cross entropy.
We use accuracy as the matrix.
Now we call the model.fit method to fit the model.
Now I find accuracy in the test data is less than accuracy in the case of train data.
We can sense that the data is overfitting.
