# Intelligent-Currency-Recognition-System

# Project Overview

**Business Value:** Built currency identification and validation system which aimed at automating global currency exchange and banking transactions. The project involved building traditional machine learning and deep learning classification models for identifying if the currencies are valid and classifying them based on the countries associated.    
# Data Source and Data Preprocessing. 

i) Scrapped more than 2500 diverse real world currency images representing 6 different currencies from google images, bing and other web portals.
ii) Augmented currency images using techniques such as scaling, flipping, cropping and rotation with a goal of making the dataset more generalized.
iii) Converted all currency images to grayscale, re-scaled them into the resoluton of 148 X 148 and stored their respective pixel values in the arrays to reduce the computational overhead.  

# Data Modeling and results

**Level 1**

i) Built traditional machine learning classification model using Ensemble Learning technique which combined the power of Random forest algorithm and Stochastic Gradient Descent Classifier algorithm resulting into 81% accuracy. 
ii) Fine-tuned classification model and implemented K Fold Cross validation in order to make model more accurate, flexible and robust. 

**Level 2**

i) Scaled dataset and involved some more categories pertaining to the currency validation in the dataset. 
i) Used same dataset and built Convolutional Neural Network classification model. 
ii) Hyper tuned the deep Learning model by tweaking dropout nodes, max pooling, early_stopping, loss function, kernel and padding values which resulted into 93.8% accuracy on test dataset. 

# Technologies Used

1) OpenCV, Scikit-image, Numpy, Pandas, Image-Generator for data pre-processing
2) Scikit learn, Matplotlib for data modelling and data visualization
3) Keras 2.0 and Tensorflow for building deep learning model, Tensor board for tracking model’s performance. 
4) Python Flask for deploying model as a web service.  

# Future Scope

1) Dive deep into the denominations and try identifying fake currency images. 
2) Involve more currencies and develop a real time dynamic currency conversion web application.  

