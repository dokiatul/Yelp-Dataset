# Yelp-Dataset
Analysis of Businesses in Yelp Dataset 

## Project Objective
Yelp is a crowd-sourced local business review and social networking site.It allows users to choose best business available and also post ratings and review about business. These reviews help business to improve their service and also respond to their customers.

The main objective of this project is to use this data of all the businesses to prepare a insightful analytics and see what are the factors which are helping current businesses to be successful and this will also help future business owners to take important decisions to establish new business. We will explore the features and use machine learning models to predict if a business can survive or not.

## Package requirements
Below are the packages we are going to use in our analysis.
1. pandas = you can find this package in anaconda navigator and install it or you can use python package manager pip,
            'pip install pandas'.Using this library to do exploratory analysis on data.
            
2. matplotlib = run 'conda install matplotlib' if Anaconda is in your system or you can use python package manager pip,
            'pip install matplotlib'.Using this library to visualize the data.

3. seaborn  = run 'conda install seaborn' if Anaconda is in your system or you can use python package manager pip,
              'pip install seaborn'. Using this library to visualize the data.
              
4. vaex = run 'conda install -c conda-forge vaex' if Anaconda is in your system or you can use python package manager pip,
              'pip install vaex'. Using this library to create a 2D interactive plot.

5. sklearn = run 'conda install -c anaconda scikit-learn' if Anaconda is in your system or you can use python package manager pip,
              'pip install scikit-learn'. Using this library to build machine learning models.

6. imblearn = run 'conda install -c conda-forge imbalanced-learn' for Ananconda or you can use python package manager pip, 
               'pip install imblearn'. This package is used to re-sample the data before training to reduce the inherent bias in the data.
              
          
## Description of Data
The Yelp dataset is download from kraggle website. It has information of about 1,74,000 businesses in multiple csv files. Below are the attributes of all csv files which are used in this analysis.

The attributes of yelp_business.csv are:                                            
. business_id                                                
. name                                               
. neighborhood                                                    
. address                                                   
. city                                                                  
. state                                                       
. postal_code                                                                             
. latitude                                                                      
. longitude                                                                             
. stars                                                                                                               
. review_count                                                                                                       
. is_open                                                                                                             
. categories

The attributes of yelp_review.css are:                                        
. review_id                                            
. user_id                                               
. business_id                                              
. stars                                         
. date                                                                                   
. text                                                                                   
. useful                                                                                 
. funny                                                                                 
. cool                                                                                   

The attributes of yelp_checkin.csv are:                                              
. business_id                                                 
. weekday                                                     
. hour                                                         
. checkins


### You can find the dataset in the below drive link:
https://drive.google.com/drive/folders/1Te0RnAWhN7vzqONzrhEB3d0XuRR1iQK8?usp=sharing

### Please download the dataset from the drive to your system. Run this file from that directory where the data is in your system or you can change the path of csv files while reading the data.

Original Source: 
https://www.kaggle.com/rksriram312/yelp-dataset-an-exploratory-analysis/data
