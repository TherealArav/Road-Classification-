# Image Classification for Road Sign Detection

A deep learning model built with TensorFlow to classify images of 
1. crosswalk
2. speedlimit 
3. stop  
4. trafficlight

#  About The Project

My first project into the world of deep learning. I built a Convolutional Neural Network (CNN) to classify five classes. The aim of this project was to learn about CNN and their application in the real world. It gave me hands on experience with real world data and working to libraries like TensorFlow and karas.

# Dataset

Source: Kaggle _By BibTeX: https://www.kaggle.com/datasets/andrewmvd/road-sign-detection_

Content: The dataset contains 877 number of images split across 4 classes.

Annotations: Labels and bounding box information are provided in corresponding XML files for each image.

Preprocessing: Resizing images to 256x256 and normalizing pixel values.

# Model Architecture

Approach: Model from scratch using Convolutional Neural Networks (16, 32, 64, 128) activation notes

Custom Layers:MaxPooling2D (2,2), Dropout (0.5) and final Dense layer (128).

Key Parameters: Optimizer (Adam), loss function (sparse_categorical_crossentropy), and accuracy (82%).

# Getting Started

Prerequisites

* Python (3.9+)
* Tensorflow (2.10+)
* Scikit-learn
* Matplotlib
* NumPy

Installation

1. Clone the repo:

    `git clone https://github.com/your_username/your_project_repo.git`

2. Install dependencies:

    `pip install -r requirements.txt`

# Results

Model Accuracy is 82%

_Note: The accuracy given represents the trained model saved in the given rep, the one in the notebook is slightly different from the orignal model._

# Insights

There are lots of improvements that can be made, as the model still overfits to a certain degree. I hope you learn something from this repository and can improve upon it.







