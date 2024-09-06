

This thesis studies the performance of various natural language processing and machine learning techniques in the tasks of sentiment analysis and usefulness scoring, including traditional TF-IDF and advanced BERT, respectively combined with logistic regression, random forest, XGBoost models, and LSTM deep learning models.

Ultimately, the following goals are hoped to be achieved:
1. Sentiment analysis model: This model predicts the sentiment of user comments based on a time series using non-overlapping comment data, which is trained and tested on a dataset split by date. By accurately identifying and analysing user sentiment, this model can help the Netflix platform better understand user viewing emotions and preferences, thereby improving the recommendation system and content optimisation strategies.
 2. Usability rating model: By modelling and training the number of ‘thumbs up’ in user comments, a usability rating model is constructed to assess the degree to which comments are helpful to other users. This model will identify the most valuable user feedback for the platform, improve the overall user experience, and optimise the content recommendation mechanism.





## Installation

！Before running the analysis code, make sure you have extracted the dataset files : netflix_reviews.zip.

！Before running the code, make sure you have installed all the required libraries in requirements.txt



## File Description

netflix_reviews.csv is the dataset for this model construction.

The Sentiment Analysis Model_TF-IDF.ipynb file contains all the sentiment analysis model codes for machine learning and deep learning models based on TF-IDF feature vectors mentioned in the paper.

The Sentiment Analysis Model_Bert.ipynb file contains all the sentiment analysis model codes for machine learning and deep learning models based on Bert feature vectors mentioned in the paper.

The Useffulness Score Model_TF-IDF.ipynb file contains all the usefulness score model codes for machine learning and deep learning models based on TF-IDF feature vectors mentioned in the paper.

The Useffulness Score Model_Bert.ipynb file contains all the usefulness score model codes for machine learning and deep learning models based on Bert feature vectors mentioned in the paper.

TF-IDF Right and BERT Wrong.ipynb file contains all the code comparing the performance of TF-IDF's and BERT's models in sentiment analysis, and outputs comments where BERT is wrong but TF-IDF is right.


##Record of project progress and plans

Plan/ How to do/ Success criteria/ Deadline

#Plan： On the Sentiment Analysis System: Data preprocessing	
#How to do： Cleaning of data, including removal of nulls, duplicates; word splitting and de-duplication of text.
#Success criteria： The dataset is free of nulls and duplicates.The text data is accurately segmented and deactivated.	
#Deadline：18/July


#Plan： Feature engineering	
#How to do： The text data is vectorized using the TF-IDF method to generate the feature matrix.	
#Success criteria： The TF-IDF feature matrix is successfully generated, and the feature matrix can effectively represent the text content.	
#Deadline：21/July


#Plan： Initial model training
#How to do： Initial training was performed using model with a TF-IDF feature matrix as input and sentiment scores as output.	
#Success criteria： A preliminary model was successfully trained, and the accuracy of the model on the training set exceeded 70%.	
#Deadline: 27/July

#Plan： Model evaluation	
#How to do： Model performance is evaluated using metrics such as accuracy, recall, and score.	
#Success criteria： 1.Obtain a full evaluation report. 2.Model has a score of 70% or more on the validation set.	
#Deadline: 29/July

#Plan： Time division experiment	
#How to do： Splitting the dataset by date, training and testing on data from different time periods, and evaluating the ability of the model to generalize over time.	
#Success criteria： 1.Successfully completed the time segmentation experiment. 2.The model performs consistently on data from different time periods, with scores varying by no more than 10 per cent	#Deadline: 1/August
			
#Plan： The "usefulness score" model: initial model training	
#How to do： Initial training was carried out using the Random Forest model with a TF-IDF feature matrix as input and a usefulness score as output.	
#Success criteria： 1.Initial Random Forest model was successfully trained. 2.The accuracy of the model on the training set is more than 70%.	
#Deadline: 8/August

#Plan： Model evaluation	
#How to do： Model performance is evaluated using metrics such as accuracy, recall, and score.	#Success criteria： 1.Obtain a full evaluation report. 2.The model has a score of 70 per cent or more on the validation set.	
#Deadline: 10/August

#Plan： Model adjustment	
#How to do： Based on the evaluation results, the model parameters are adjusted, and the model is tested.	
#Success criteria： 1.Successfully adjust the model and test the model. 2.The tuned model scores more than the initial model on the validation set.	
#Deadline: 14/August


