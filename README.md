# Prediction of Autism in Kids

The Project Prediction of Autism in Kids was undertaken as a course project as part of the MLOps and ML System Design Course during Term 5 at the Indian Institute of Management, Bangalore. The project was completed under the guidance of  Prof. Manaranjan Pradhan.
-- Project Status: Completed

## Objective:
The purpose of this project is predict the presence of autism in toddlers below the age of 36 months. 
Autistic Spectrum Disorder (ASD) is a neurodevelopmental condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods. Therefore, a time-efficient and accessible ASD screening is imminent to help health professionals and inform individuals whether they should pursue formal clinical diagnosis. 
The rapid growth in the number of ASD cases worldwide necessitates datasets related to behaviour traits. However, such datasets are rare making it difficult to perform thorough analyses to improve the efficiency, sensitivity, specificity and predictive accuracy of the ASD screening process. Presently, very limited autism datasets associated with clinical or screening are available and most of them are genetic in nature. This autism screening of toddlers contains influential features to be utilised for further analysis especially in determining autistic traits and improving the classification of ASD cases. In this dataset, ten behavioural features (Q-Chat-10) plus other individuals characteristics that have proved to be effective in detecting the ASD cases from controls in behaviour science, have been taken.

## Methodology Used:
1. Data Profiling
2. Exploratory Analysis & Feature Engineering
3. Building Machine Learning Models
4. Model Experiments 
5. Model Deployment
6. Model Monitoring and Explainability 

## Technologies:
1. Python and Python Packages (Numpy, pandas, scikitlearn, seaborn, matplotlib, tensorflow, keras etc)
2. Weights and Biases, for Experiment tracking
3. Google Colab
4. Gradio, for UI

## Problem and Dataset Overview:
The dataset we have taken for predicting ASD syndrome consists of 1054 children in the age group of 12-36 months. Out of the 1054 observations, there are a total of 728 positive class (i.e., children having ASD traits and requiring further medical care). There are a total number of 18 variables (including the output variable). The remaining variables are of categorical nature and form the crux of the dataset. The categorical variables which make up the bulk of total variables, namely A1-A10, are subjective behavioural questions that have been answered about the children’s emotional development.

Dataset : https://www.kaggle.com/furkan1903/autism-screening-data-for-toddlers/data

Task: Classification

Attribute Type: Categorical, continuous and binary

Area: Medical, health and social science

Format Type: Non-Matrix

Number of Instances (records in your data set): 704

Number of Attributes (fields within each record): 21


## Attribute Information:
Attribute Type: Description
1. Age: Number Age in years
2. Gender: String Male or Female
3. Ethnicity: String List of common ethnicities in text format
4. Born with jaundice Boolean (yes or no) Whether the case was born with jaundice
5. Family member with PDD Boolean (yes or no) Whether any immediate family member has a PDD
6. Who is completing the test String Parent, self, caregiver, medical staff, clinician, etc.
7. Country of residence String List of countries in text format
8. Used the screening app before Boolean (yes or no) Whether the user has used a screening app
9. Screening Method Type Integer (0,1,2,3) The type of screening methods chosen based on age category (0=toddler, 1=child, 2= adolescent, 3= adult)
10. Question 1 Answer Binary (0, 1) The answer code of the question based on the screening method used
11. Question 2 Answer Binary (0, 1) The answer code of the question based on the screening method used
12. Question 3 Answer Binary (0, 1) The answer code of the question based on the screening method used
13. Question 4 Answer Binary (0, 1) The answer code of the question based on the screening method used
14. Question 5 Answer Binary (0, 1) The answer code of the question based on the screening method used 
15. Question 6 Answer Binary (0, 1) The answer code of the question based on the screening method used
16. Question 7 Answer Binary (0, 1) The answer code of the question based on the screening method used
17. Question 8 Answer Binary (0, 1) The answer code of the question based on the screening method used
18. Question 9 Answer Binary (0, 1) The answer code of the question based on the screening method used
19. Question 10 Answer Binary (0, 1) The answer code of the question based on the screening method used
Screening Score Integer The final score obtained based on the scoring algorithm of the screening method used. This was computed in an automated manner.

## Getting Started:
1.	Clone this repo (for help see this tutorial).
2.	Raw Data in different formats is stored under the Data folder 
3.	All models are present under the Development repo folder 
4.	For deploying the model UI, the Autism Screening Prediction App under the Deployment repo folder needs to be run
5.	All Reports, including data profile report, Experiment tracking and Performance Reports are present under the Reports repo folder

## Featured Notebooks:
Access Link for all Notebooks:  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thisisSHAX/ML_Ops_Project-/)

## References:
1. Tabtah, F. (2017). Autism Spectrum Disorder Screening: Machine Learning Adaptation and DSM-5 Fulfillment. Proceedings of the 1st International Conference on Medical and Health Informatics 2017, pp.1-6. Taichung City, Taiwan, ACM.
2. Thabtah, F. (2017). ASDTests. A mobile app for ASD screening. www.asdtests.com [accessed December 20th, 2017].
3. Thabtah, F. (2017). Machine Learning in Autistic Spectrum Disorder Behavioural Research: A Review. To Appear in Informatics for Health and Social Care Journal. December, 2017 (in press)

## The Team:
1. Shashwat Jain (https://github.com/thisisSHAX)
2. Aishwarya Nair (https://github.com/MayTune)
3. Samarth Gubrele (https://github.com/Sam5cool)
4. Shanmugaraja S
5. Sanjoy Podder

Please feel free to contact the team with any questions or if you are interested in contributing!
