# Face Recognition Using CNN

Facial recognition is a way of identifying or confirming an individual's identity using their face. Facial recognition systems can be used to identify people in photos, videos, or in real-time.

# Installation

First you need to install the requirements:

1- install Anaconda : https://www.anaconda.com/download/

2- Jupyter notebook (conda install jupyter)

3- conda install scipy

4- install other requirements

    pip install sklearn
    pip install pandas
    pip install pandas-datareader
    pip install matplotlib
    pip install pillow
    pip install requests
    pip install h5py
    pip install tensorflow==1.8.0
    pip install keras==2.2.0
    pip install opencv-python
    pip install opencv-contrib-python
    
 # Dataset
  
  The dataset is ORL_faces.npz consists 400 different face images from 40 distinct subjects.
  
  you must extract the zip file into code folder
  
# Usage
  
  You can see the results of the code that has already been executed. Run, restart, and execute all from the notified to rerun the code.
  After loading the database first we need to convert the format of image into float. 30% of dataset is used as a validation dataset. Using sequential model of keras I create a CNN model layer by layer which are convolutional layer, pooling layer, fully connected layer. The model is trained over 300 epochs. and at last the accuracy is around 93%.
  
 # Result 
 ![Output](https://github.com/MeghaChawala/Face-recognition/blob/main/Result%20(1).jpg)
 
 # Road-map
 I can employ more distinct types of categories in the future work that would be tough for the computer to classify and compare more advanced classifiers.
