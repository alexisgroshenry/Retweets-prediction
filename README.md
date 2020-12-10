# Retweet prediction

## Preprocessing

The preprocessing is in two steps. Firstly, run "Preprocessing_sentiment". There is a neural network to train based on these [data](https://www.kaggle.com/kazanova/sentiment140 ) to train. You need to download it also.
All data files need to be in a folder called "data".

Secondly, you need to run the "Preprocessing_data" to preprocess almost everything we need. For that, you will need the two files that were written in the first script : "training_v1.npy" and "evaluation_v1.npy". 

## Model training

Run the "Training_model". It will create a file in the *results* folder with the submission.
