# DisasterTweets
# Data:
https://www.kaggle.com/competitions/nlp-getting-started/overview

In this kaggle competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. Dataset consisits of of 10,000 tweets that were hand classified.

Each sample in the train and test set has the following information:

The text of a tweet

A keyword from that tweet (although this may be blank!)

The location the tweet was sent from (may also be blank)

Files:

train.csv - the training set

test.csv - the test set

sample_submission.csv - a sample submission file in the correct format

Columns:

id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

Steps of the project:

Load the Disaster Tweets
Explore the dataset
Preprocess the data
Load a deBERTa model from transformers
Train model, fine-tuning deBERTa
Generate the submission file

# Results:
![image](https://github.com/AlisherAmirbek/DisasterTweets/assets/124807619/70b409f8-a4de-43bc-a5cf-11a85e520672)

