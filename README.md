# CNN_Car_recognition
CNN deep learning model for the recognition of damaged and undamaged cars.

## Background
The image recognition convolution neural network differentiates between damaged and undamaged cars. The network was trained against a dataset containing images of cars or cars involved in accidents. Additional random images were included to increase the generality of the classifier. Visual examination of feature maps pertaining to each filter for individual layers of the network indicated that the model generated in these studies retained significant information from the input images.

## Conclusions
The CNN network (model N) generated in these studies performed well with reasonably good accuracy and correctly predicting 6 out 7 random images taken from a test dataset. Due to difficulties in getting the images into a suitable format on the Google Colab server it was not possible to calculate additional measures of performance (e.g. confusion matrix, F1 score, precision and recall). Transfer learning using feature extract and utilizing the VG16 convolutional network did not perform well due to overfitting. Fine tuning produced a better result, similar to that of the generated CNN network (model N), with significantly less overfitting. Examination the feature maps suggested that this CNN network (model N) effectively captured information from images within the training dataset.

 Note: See file **Deep Learning CNN Model for Vehicle Accident Recognition.pdf** for further information describing the development and testing of the CNN model.
