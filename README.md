# Facial-Emotion-Recognition

## Problem Description
![alt text]( https://github.com/coolamit1232/Facial-Emotion-Recognition/blob/master/Output/Readme.JPG "Problem Description")

Facial Emotion Recognition is a process of detecting human emotions from facial expressions.
Thanks to DL, for giving us computer animated agents and robots which bring new dimension in human computer interaction.

Here, our goal is to detect expressions mentioned above either in an image or a live video containing faces of humans. However, the model is going to take faces from this images and find expressions for each face.
 
This project is based on convulational neural network (CNN) to classify images into seven most common human expressions that are: **ANGER, DISGUST, FEAR, HAPPY, NEUTRAL, SAD, SURPRISE**.


## Dataset
Dataset contains 28,709 training and 7,178 testing images, each of size 48x48. \
There is a directory for each expression type containing images of that expression only

### Link : https://www.kaggle.com/msambare/fer2013


# How to Run the Model

After downloading data from the above ementioned sources: 
 1. For real time prediction you can run the file "Run.ipynb".
 2. Or you can create or modify CNN model in the file Model i.e "Facial Emotion Recognition.ipynb" to train the model. You can add or delete layers in MLP part of the model based on your data and results. Don't forget to save your model after each epoch.


# Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.

+ Python 3
+ Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, PIL.
+ OpenCV
+ keras

