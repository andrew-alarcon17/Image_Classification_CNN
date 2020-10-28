# Image_Classification_CNN

## Data Description:
This data contains images that belong to the following 10 classes:
-Airplanes
-Cars
-Birds
-Cats
-Deer
-Dogs
-Frogs
-Horses
-Ships
-Trucks
There are 6,000 images for each class, and each image has a low resolution.
Here are a few examples of how the images look:

<img src="https://github.com/andrew-alarcon17/Image_Classification_CNN/blob/main/Visualizations/Predictions.png" width="500">

## Project Summary:
For this project, I will be creating a Convolutional Neural Network that will be able to classify the images in the data set.

## Findings:
Before training the model on the training data, I compiled the model using a loss of cross_entropy (because of the nature that this model is under classification).
The model was then fitted to the training data with a batch size of 32, which is how many images were fed to the network at once.
The accuracy ended up being .565. I then had the model predict on the testing data, and these were the results:

<img src="https://github.com/andrew-alarcon17/Image_Classification_CNN/blob/main/Visualizations/Sample_Images.png" width="700">
