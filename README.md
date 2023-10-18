# Twitter-Sentiment-Classification

Twitter is a great open source of textual data for training specific natural language processing tasks, considering that there are millions of users expressing their own opinions, emotions or experiences regarding various matters every day. For this, Twitter sentiment analysis is chosen to be the task of interest by many researchers or marketers to investigate how people feel towards certain topics, products, brands, etc.

Within the scope of the project, however, we will solely focus on building, assessing and comparing several machine learning models that are trained specifically for sentiment analysis. The complexity of the models varies from as simple as a Logistic Regression model to a higher level such as the GRU. The main point of the project is to understand how different levels of model complexity affect the classification result with the available resources, given that the average sequence length is short and can be easily modelled. The project should show how the model complexity choice reflects the task complexity, and hopefully give us insights into the importance of pre-evaluation of tasks before modelling.

The project will consist of the following stages:

- Data cleaning:
  - Removing noises.
  - Negation handling.
- Data modelling
  - Scikit-learn models:
    - TF-IDF encoding.
    - Logistic Regression model. 
    - Naive Bayes model.
  - PyTorch models:
    - GloVe encoding.
    - Feed-forward neural network (FNN).
    - Bi-directional Recurrent neural network (RNN). 
    - Convolutional neural network (CNN).
    - Bi-directional Gated Recurrent unit (GRU).
- Model evaluation and comparisons
