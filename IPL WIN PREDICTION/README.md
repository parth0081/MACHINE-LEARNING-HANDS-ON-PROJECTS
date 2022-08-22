Since its introduction in 2003, T20 has become the star attraction within cricket for its high voltage action and exciting phases of play. As part of its popularity, the IPL (Indian Premier League), formed in 2008, began and kicked off one of the largest annual sports events in the world alongside the Football Premier League and NBA (National Basketball Association) until today. As a result of its increasing demand, teams are spending money towards a variety of avenues to gain a distinct competitive edge. One of these avenues is within data science to analyse player performance and opposition performance. As a result, the analysis of a league like this IPL is of growing importance. The data found from Kaggle. It uses two sets of data based from 2008 -2017; match-by-match and ball by ball statistics. The datasets are suitable to extract some key data, provide some statistical descriptive and visualizations and apply some machine learning techniques using Python.


![image](https://user-images.githubusercontent.com/68374336/185886558-52dcd98c-0217-48de-88c8-be2437611d51.png)

![image](https://user-images.githubusercontent.com/68374336/185886707-82d500db-6813-4910-b240-986063b5abb5.png)



## IPL Win Probability Predictor



* IPL Dataset analysis: This analysis includes checking for null values and replacing them, describing the dataset’s feature columns, and analyzing each feature.

* Data Wrangling- Removal of null values and basic preprocessing is done .

* Performed preprocessing techniques on the IPL Data: Performed several feature engineering techniques in order to make the dataset suitable for making the model. Encoding for converting categorical features to numerical features and techniques to avoid null values are used.

* Model creation and Evaluation: This was the main part of the project, and we used the RandomForestClassifier model. Later we tested this model with the test set for evaluation.


In this project, I have two models:

#### a) Logistic Regression- 
This model is giving the accuracy score of : 0.807336274764253

#### b) Random Forest Classifier-
This model is giving the accuracy score of : 0.9988753352366122

But here I have chosen Logistic Regression as my Predictor as it is not giving  the accuracy 'one-sided' as in the case of Random Forest Classifier.
