# TMDB-Box-Office-Prediction-Kaggle

In a world… where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? For some movies, it's "You had me at 'Hello.'" For others, the trailer falls short of expectations and you think "What we have here is a failure to communicate."

In this competition, you're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. You can collect other publicly available data to use in your model predictions, but in the spirit of this competition, use only data that would have been available before a movie's release.

Steps to execute:

1. First, Run a jupyter notebook server ($ jupyter notebook).
2. Open the Preprocessing & visualizations.ipynb file and run all the lines. (This will generate 2 csv files preprocessed_train_data.csv & preprocessed_test_data.csv)
3. Open the regressor model(Please select ipython file name which doesnot contain word Basic.For ex DecisionTree_Regressor.ipynb) you wish to try 
   and run all the lines in that file. (This will generate a tmdb-box-office-prediction.csv file)
4. Upload the file on kaggle to check the accuracy of that model.


Contents of the project are :-

1.Project 2_ Report_DataScience.docx
2.DecisionTree_Regressor.ipynb
3.DecisionTreeRegressor_Basic.ipynb
4.KNNRegressor.ipynb
5.KnnRegressor_Basic.ipynb
6.Linear Regression.ipynb
7.Linear Regression_Basic.ipynb
8.Preprocessing_Data_Visualization.ipynb
9.Random Forest_Basic.ipynb
10.Random_Forest.ipynb
11.SVMRegressor.ipynb
12.SVMRegressor_Basic.ipynb
13.preprocessed_test_data.csv
14.preprocessed_train_data.csv
15.test.csv
16.train.csv

Important Note:
The accuracy may vary since the code uses GridSearch.
