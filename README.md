# Intelligent Currency Recognition System

# Project Overview

**Business Value:** Built currency identification and validation system which aimed at automating global currency exchange and banking transactions. The project involved building traditional machine learning and deep learning classification models for identifying if the currencies are valid and classifying them based on the countries associated.    
# Data Source and Data Preprocessing. 

i) Scrapped more than 2500 diverse real world currency images representing 6 different currencies from google images, bing and other web portals.

ii) Augmented currency images using techniques such as scaling, flipping, cropping and rotation with a goal of making the dataset more generalized.

iii) Converted all currency images to grayscale, re-scaled them into the resoluton of 148 X 148 and stored their respective pixel values in the arrays to reduce the computational overhead.  

# Data Modeling and Results

**Level 1**

i) Built traditional machine learning classification model using Ensemble Learning technique which combined the power of Random forest algorithm and Stochastic Gradient Descent Classifier algorithm resulting into 81% accuracy. 

ii) Fine-tuned classification model and implemented K Fold Cross validation in order to make model more accurate, flexible and robust. 

**Level 2**

i) Scaled dataset and involved some more categories pertaining to the currency validation in the dataset. 

ii) Used same dataset and built Convolutional Neural Network classification model. 

iii) Hyper tuned the deep Learning model by tweaking dropout nodes, max pooling, early_stopping, loss function, kernel and padding values which resulted into 93.8% accuracy on 
test dataset. 

# Technologies Used

i) **Data Pre-processing:** OpenCV, Scikit-image, Numpy, Pandas, Image-Generator.

ii) **Data Modelling and Data Visualization:** Keras 2.0 and Tensorflow, Scikit learn, Matplotlib.

iii) **Model Performance and Maintenance:** Tensor board. 

iv) **Model Deployment:** Python Flask 

# Future Scope

i) Dive deep into the denominations and try identifying fake currency images. 

ii) Involve more currencies and develop a real time dynamic currency conversion web application.  

