# Topic Modeling for Research Articles

Researchers have access to large online archives of scientific articles. As a consequence, finding relevant articles has become more difficult. Tagging or topic modelling provides 
a way to give token of identification to research articles which facilitates recommendation and search process.

The main aim of this project is to predict the topics for each article with best micro f1_score based on given the abstract and title for a set of research articles by going through below steps:

Step 1: Giving a look into the dataset's features through some simple EAD                                    
Step 2: Performing all the below steps in preprocessing:                                          
* Data cleaning
* Convert text data into Vectors
* Create new features from existing features    

Step 3: Finding variables that are most predictive of the topics.                                                             
Step 4: About Modeling: Logistic Regression, LinearSVC, SGDClassifier and various ensemble models were used in fitting the data with hyper parameter tuning.

The research article abstracts and titles are sourced from the following 6 topics: 
1. Computer Science
2. Physics
3. Mathematics
4. Statistics
5. Quantitative Biology
6. Quantitative Finance
