# Hand Written Digit Recognition
 Hand Written Digit Recognition using javascript library tensorflowjs
 
## Installing
Clone this repository to your local computer
``` bash
git https://github.com/bensonruan/Hand-Written-Digit-Recognition.git
```
Point your localhost to the cloned root directory

Browse to http://localhost/index.html  

## Start Predicting Hand Written Digit
* Draw on the canvas with your mouse on desktop or your finger on your mobile
* Click "Predict" to get result of the hand written digit prediction
* Click "Clean" to start drawing again

## Pre-trained model 
Use MNIST dataset from Keras with CNN (Convolutional Neural Network)
* model.add(Convolution2D(32, (5, 5), border_mode='valid', input_shape=(28, 28, 1), activation='relu'))
* model.add(MaxPooling2D(pool_size=(2, 2)))
* model.add(Dropout(0.2))
* model.add(Flatten())
* model.add(Dense(128, activation='relu'))
* model.add(Dense(num_classes, activation='softmax'))

## Library
* [jquery](https://code.jquery.com/jquery-3.3.1.min.js) - JQuery
* [tensorflowjs](https://github.com/tensorflow/tfjs) - JavaScript library for training and deploying machine learning models
* [Chart.js](https://github.com/chartjs/Chart.js) - JavaScript library for display charts
