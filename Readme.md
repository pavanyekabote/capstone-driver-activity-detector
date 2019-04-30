# Capstone Project - Machine Learning NanoDegree
Capstone project for Udacity's Machine Learning Engineer Nanodegree

### Problem Statement
A dataset of 2D images containing a driver, performing an activity, are given. An algorithm has to be developed to classify the activity of driver within the given classes and determine if they are driving attentively, or getting distracted taking selfies and performing other interruptive activities.This can be used to automatically detect drivers engaging in distracted behaviour, while driving, from dashboard cameras.

### Dataset Files description

Following are the file descriptions and the URL’s from which files have been obtained.
* ```Imgs.zip```	           -  A zip file containing all train and test images
* ```driver_imgs_list.csv```  - A list of training subject ids, class names and respective images.  
* ```sample_submission.csv``` - A sample format for submission to calculate the evaluation metrics.

 The following link will download a zip file of all above listed files: 
*	https://www.kaggle.com/c/5048/download-all 



Following are the details of Software environments with version details :
```
* Python 3.6.0 :: Anaconda 4.3.1 (64-bit)
* Tensorflow 1.1.0
* Keras 2.0.4
* Numpy 1.15.4
* Pandas 0.23.4
```

Submissions are available in sub_outs folder, where sub.csv is of CNN from scratch and sub_VGG16 is of VGG16_finetuned model
