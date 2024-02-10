# Flower-Classification
Machine Learning Assignment Solution

This repository contains code for a flower classification project. 

The Components of Project are:

1)	Load and Preprocess Images: Code to load flower images from a directory, preprocess them, and split them into training, validation, and test sets.
2)	Annotate Images with Bounding Boxes: Code to annotate flower images with bounding boxes using OpenCV and save the annotations to a JSON file.
3)	Train Flower Classification Model: Code to train a convolutional neural network (CNN) model for flower classification using TensorFlow and Keras.
4)	Classify Input Image: Code to classify a single input image into one of the predefined classes using the trained model.

Requirements: 

1)	Python 3.x
2)	OpenCV
3)	NumPy
4)	TensorFlow
5)	scikit-learn

Instructions:

1)	Load and Preprocess Images: Update the data_directory variable with the path to the directory containing the flower images. Adjust the image_size variable to the desired image size for resizing. Run the code to load and preprocess the images.
2)	Annotate Images with Bounding Boxes: Update the data_directory variable with the path to the directory containing the flower images. Run the code to annotate the images with bounding boxes and save the annotations to a JSON file.
3)	Train Flower Classification Model: Update the data_directory variable with the path to the directory containing the flower images. Adjust the image_size variable to match the image size used for preprocessing. Run the code to train the flower classification model.
4)	Classify Input Image: Update the input_image_path variable with the path to the input image. Run the code to classify the input image using the trained model.

Installing:

If you are facing any issues with missing libraries, the following command is used for installing them:

pip install library_name (If you are installing in cmd)
        						or
!pip install library_name (If you are working in Jupyter Notebook)
