# Gender-Classification-Using-InceptionV3

The following project was implemented on Google Colaboratory. The datasets referred were from [here](https://github.com/laxmimerit/male-female-face-dataset).

**Inception V3** is a convolutional neural network for assisting in image analysis and object detection.
We have imported the package from [here](https://github.com/fchollet/deep-learning-models/releases/tag/v0.2)

1) We first clean the images, by resizing, rescaling, exporting the rgb and features of the images.
2) Then the model is trained with the help of layers created, finally the accuracy of the model is found.
3) Later we use a test image, upload the .jpg file to the google colab directory and this way manually classify the gender of the person.
4) Another way we have implemented to do so is by capturing a photo of the user, save it and run it to our made model.
( The basic open CV code which goes behind it can be found on the web, which makes it easier for an ML enthusiast to quickly implement ).
Finally the model prints the gender of the photo.
