# NACME/AMLI Google Bootcamp

The NACME-Google AMLI Summer Bootcamp aims to provide students with an introduction to computer science content to qualify for entry-level Machine Learning Specialists positions. This program prepares talent to understand and apply statistics and machine learning to solve real-world data science problems. The boot camp aims to expose Under-Represented Minority students to advanced artificial intelligence/machine learning concepts using Google's curriculum. The curriculum will enable NACME partner institutions to give students the foundation to work with large datasets and solve real-world problems.

# Team

Alliayah Ottley - Morgan State University 

Breahna Fox - Morgan State University

Femi Epps - Morgan State University

Thomas Goodman - Morgan State University 

# Facial Expression Recognition

Use the Kaggle Facial Expression Recognition dataset to train a Convolutional Neural Network model that can categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

![image](https://repository-images.githubusercontent.com/267105580/d6d64080-d51f-11eb-8957-e8156c334a72)

# Obtaining Dataset
For our project, we were given a dataset based on the website, Kaggle, which we have been using during our time in this curriculum. This folder contains the images we are going to use for our recognition analysis. There is a link below that will guide you to the folder that contains over 35,000 images of various facial expressions 

https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset/code 

# Exploring Data
Exploratory data analysis is the process of examining a dataset to find facts about the data and communicating those facts, often through visualizations. Through the use of visualizing our images, we were able to show that not only do we have the images in our project, but we are also able to call them based on desired emotion. Not only this but we're also able to count the number of images in each section of the dataset that we used. 

![image](https://images.indianexpress.com/2022/05/Facial-search-engine-featured.jpg)

# Modeling
As detailed earlier in the article we are trying to build a system that can sort through and categorize the different emotions based on facial expressions. This can best be done by building a Convolutional Neural
Network model. A convolutional neural network model is a deep learning algorithm that can take an object, were focusing on images, and be able to sort them. This aligns perfectly with how would like to operate with our project

![image](https://docs.ecognition.com/Resources/Images/ECogUsr/UG_CNN_scheme.png)

# Measurement indicators 
In our project, we are tasked with using different indicators to present how well our model was at predicting and categorizing. The accuracy score is used to measure the performance of the model in measuring the ratio of the sum of the true positive and true negative values ​​from all the predictions made. The precision score is used to measure the performance of the model in correctly measuring the number of true positives from all positive predictions made.
The recall value is a useful measure of predictive success when the class is very unbalanced. F1-score is the harmonic mean of precision and recall score.
All of these tools will be used to show how well the model is. 

![image](https://1.bp.blogspot.com/-b_lbkGbwKCo/W-lK6MZ3-xI/AAAAAAAAAYA/uuAkY-KkyEAdSJPxJKRaam0qQoMo9wZ4ACLcBGAs/s1600/2.PNG)

# Usage Instructions
1. Ensure that at least 8GB of ram is available to process the images and train the model. 
2. Create a Kaggle account and download a json file
3. Go to google colab and create a new notebook
4. Upload the json file to the colab
