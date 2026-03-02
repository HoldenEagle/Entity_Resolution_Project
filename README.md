# Entity_Resolution_Project

In this project, our goal is to match the article authors dataframe and the grantees dataframe 
together. To handle matching even in the prescence of mispellings or missing entries, we plan
to build a machine learning model to map entries together. In this code, we build the training 
dataset to achieve this, using fasttext's word encoding to help us build features. We compare 
different rows of articles and grantees together, using the word encoding to get the difference
between their last name, surname, email, and intials. 