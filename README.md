# Topic Modeling for Research Articles

Business Objective:
The main aim of this project is to predict the topic for each article with best micro F1 Score based on the given abstract and title features for a set of research articles

Synopsis:                                                                                          
•	Giving a look into the dataset's features through some simple EAD                                 
•	Performing all the below steps in pre-processing:                                     
o	Data cleaning by removing stop words, special characters and visualise most frequent words with the help of Word Cloud
o	Feature extraction by expected new features from existing features                                                 
o	Convert text data into Vectors by using TF-IDF Vectorizer and find the best n-grams with the help of RandomizedSearchCV that are most predictive to the topic prediction         
•	About Modeling: Logistic Regression, LinearSVC, SGDClassifier and various ensemble models were used in fitting the data with hyper parameter tuning

The research article abstracts and titles are sourced from the following 6 topics:                                              
•	Computer Science                                                                
•	Physics                                                 
•	Mathematics                                                           
•	Statistics                                                                                                    
•	Quantitative Biology                                                                                          
•	Quantitative Finance                                                     
