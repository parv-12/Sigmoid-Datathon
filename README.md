# Sigmoid-Datathon
This repository contains our approaches on the Emotion Classification Task in the [Sigmoid Data Science Hackathon](https://www.hackerearth.com/challenges/competitive/sigmoid-data-science-hackathon-machine-learning-challenge/) 

Contributors - Ramashish Gupta, Archit Mangrulkar, Parv Jain, Harsh Khandelwal  

The focus of sentiment analysis is to derive information from human language for interpreting views and feelings to assign polarities like positive, negative, or neutral. However, emotion detection aims at finding out more specific sentiment tones such as happiness, sadness, depression, anxiety, etc. Emotion detection can be applied to different types of unstructured data with text being one of such types of data.

## Model files here -> [link](https://iitkgpacin-my.sharepoint.com/personal/ramashisx_kgpian_iitkgp_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Framashisx%5Fkgpian%5Fiitkgp%5Fac%5Fin%2FDocuments%2Fsigmoid&ga=1)
Task:
Predict emotions from posts, reviews, blogs, or tweets that focus on a product/ service experience. Each query of the test data can have one or all of the emotions tagged to it.

Dataset description:
The dataset contains the following files: train.csv: 7724x14 test.csv: 400x2 sample_submission.csv: 10x14

The columns provided in the dataset are as follows- 
![](https://github.com/architmang/sigmoid-datathon/blob/main/column%20description.png)

We achieved an F1-score of 0.5945 using an ensemble of Roberta models for anger, neutral and other classes
