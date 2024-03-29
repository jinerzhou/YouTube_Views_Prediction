# YouTube Views Prediction - For Fitness Videos

#### Summary </br>
This project focuses on developing a machine learning model that predicts the approximate number of views that a YouTube Fitness video will receive, using various input features such as the title / description / tags of the video, the video length (in seconds), and the content creator’s channel popularity (views, subscribers count, and videos count).
This model will assist Fitness content creators (primarily in the United States) in estimating the potential impact of their videos and adjusting video-related information to improve viewer engagement and monetization opportunities. </br>

#### Problem Statement </br>
Content creators on YouTube often struggle to estimate the potential viewership of their upcoming videos, which limits their ability to maximize their video's impact and monetization opportunities. The proposed solution is to create a machine learning model that predicts the approximate number of views that a YouTube video is likely to receive, based on various input features such as video metadata and the creator's channel statistics. This model will help fitness content creators to optimize their video-related information and enhance viewer interaction with potential revenue-generating possibilities. To utilize this model, content creators are required to input their video’s title, description, tags, length (in seconds), as well as their channel ID, and the model will output the predicted number of views of the video. 
Due to the sheer scale of the problem, I have limited my focus to a single video category, Fitness, and restricted it to the US region. </br>

#### Project
To start the project, a dataset of around 25K fitness-related videos on YouTube in the US from 2020-2023 was gathered using the YouTube Data API v3. After dealing with the daily API usage limit, the data underwent feature engineering and exploratory data analysis. The data was then preprocessed and split into training and testing sets. A range of machine learning models were utilized to determine the optimal one. These models included numerical models like random forest and decision tree, as well as text models such as bag-of-words, TF-IDF, MLPClassifier, and RidgeCV. Additionally, pipelined models that combined both numerical and text models with linear regression were implemented with the aim of improving performance, and hyperparameters were tuned accordingly. Selected features such as video title, description, tags, length, channel views, subscribers count, and videos count were utilized to identify the best performing model. A user interface was developed that takes user inputs, processes data, runs the best model for predictions, and returns the results to the user. </br>


Flowchart: </br>
●	 Collect fitness-related videos dataset from YouTube </br>
●	 Preprocess the data, perform exploratory data analysis, and feature engineering </br>
●  Split the data into training and testing sets </br>
●  Train multiple machine learning models via various methods </br>
●	 Evaluate the performance of each model and select the best performing one </br>
●	 Create the final pipelined machine learning models to predict the number of views for upcoming fitness videos on YouTube </br>
●	 Develop user interaction to take user inputs and compute predictions </br>
●	 Utilize the model to estimate the potential impact of upcoming videos and adjust the video-related information accordingly </br>

