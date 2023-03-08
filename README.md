Image Super Resolution using Autoencoder
This is a project on Image Super Resolution using Autoencoder. It is implemented using TensorFlow and Keras libraries in Python.

1.  Introduction
The aim of this project is to train an autoencoder model to increase the resolution of low-resolution images. The model will take a low-resolution image as input and generate a high-resolution image as output.

2.  Dataset
The Labeled Faces in the Wild (LFW) dataset is used for this project. It contains face images of various sizes and resolutions.

3.  Implementation
The implementation of this project is done in the following steps:

- Reading the image files and converting them to arrays.
- Preprocessing the images by reducing their resolution and increasing it back to create the low-resolution images.
- Building the autoencoder model using convolutional neural network (CNN) layers.
- Training the model on the low-resolution images and their corresponding high-resolution images.
- Evaluating the model on the validation set and visualizing the results.
4.  Usage
The notebook Image_SuperResolution.ipynb contains the entire implementation of the project. It can be run on Google Colab or any other Jupyter notebook environment.

5.  Conclusion
This project shows how autoencoder can be used to increase the resolution of low-resolution images. The results obtained from the model show that it is able to generate high-resolution images from low-resolution ones. This technique has many practical applications in image processing and computer vision.