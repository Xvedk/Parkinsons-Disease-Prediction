# Parkinsons-Disease-Prediction
In this project, the goal is to predict Parkinson's disease using a dataset that includes various clinical voice measurements. The dataset is loaded and preprocessed by dropping irrelevant columns and splitting it into training and testing sets. To enhance the predictive model's performance, Min-Max scaling is applied to normalize the numeric features. An XGBoost classifier is then trained on the scaled data to predict the presence or absence of Parkinson's disease. The model's accuracy and classification report are evaluated on the test set. 

Data Set Information:
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). 

Attribute Information:

Matrix column entries (attributes):

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%) , MDVP:Jitter(Abs) , MDVP:RAP , MDVP:PPQ , Jitter:DDP - Several measures of variation in fundamental frequency

MDVP:Shimmer , MDVP:Shimmer(dB) , Shimmer:APQ3 , Shimmer:APQ5 , MDVP:APQ , Shimmer:DDA - Several measures of variation in amplitude

NHR , HNR - Two measures of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE , D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1 , spread2 , PPE - Three nonlinear measures of fundamental frequency variation

Exploratory Data Analysis

**#Counter-Plot**

![1](https://github.com/Xvedk/Parkinsons-Disease-Prediction/assets/124188416/2137b8b9-1034-4c0e-9703-2b3c5a27c425)

**#Heat-Map**

![2](https://github.com/Xvedk/Parkinsons-Disease-Prediction/assets/124188416/91242bae-67d8-44e7-96e1-e86818dc5bfa)

**#Pair_plot**

![3](https://github.com/Xvedk/Parkinsons-Disease-Prediction/assets/124188416/90f14aaa-cb9b-4cf4-8a26-dde4c86c8289)

**#Pie-Chart**

![4](https://github.com/Xvedk/Parkinsons-Disease-Prediction/assets/124188416/dd4d7a2d-88c6-4727-aef8-55124288390c)



