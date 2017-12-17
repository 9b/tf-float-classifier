TF Float Classifier
===================
Tensorflow classifier that can classify images with float numbers and detect the actual value.

Training Data
-------------
Several free fonts were downloaded from FontSquirrel_ and fed into a program to generate images of text showing 0.0 through 10.0 incremented by 0.1 steps. Each line in the training CSV is that of a float number, font used and base64 version of the generated image.

.. _FontSquirrel: https://www.fontsquirrel.com/

Image Details
-------------
All images are 50x50 in size, black and white in color and use a font size of 25px.