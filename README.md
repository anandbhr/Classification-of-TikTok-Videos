# Classification-of-TikTok-Videos

## Project Overview

In this project consider that you are working as a data professional at TikTok and you have been assigned a project to classify Tiktok Videos as Claims or Opinions

TikTok users have the ability to report videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. This process generates a large number of user reports that are difficult to address quickly. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently. 

## Project Steps

This project is divided into 4 steps:

1. Exploratory Data Analysis : TikTok’s data team is working on the claims classification project. The following tasks are needed before the team can begin the data analysis process- EDA and cleaning, Select and build visualization type and Create plots to visualize variables and relationships between variables

2. Hypothesis Testing : In this step you are asked to a conduct hypothesis testing on the data for the claims classification data. You’ve been asked to investigate TikTok's user claim dataset to determine which hypothesis testing method best serves the data and the claims classification project.

3.  Build a Logistic Regression Model : The following tasks are needed at this stage of the project - Determine the correct modeling approach, Build a regression model, Finish checking model assumptions and Evaluate the model.

4.   Build a Machine Learning Model : In this part, You will create the final machine learning model for the claims classification data. You will be responsible for leading these final tasks, which include feature engineering, model development, and evaluation.

## Conclusion

TikTok videos receive a large number of user reports for many different reasons. Not all reported videos can undergo review by a human moderator. Videos that make claims (as opposed to opinions) are much more likely to contain content that violates the platform’s terms of service. TikTok seeks a way to identify videos that make claims to prioritize them for review.
The data team built two tree-based classification models. Both models were used to predict on a held-out validation dataset, and final model selection was determined by the model with the best recall score. The final model was then used to score a test dataset to estimate future performance.

Both model architectures—random forest (RF) and XGBoost—performed exceptionally well. The RF model had a better recall score (0.995) and was selected as champion.
Performance on the test holdout data yielded near perfect scores, with only five misclassified samples out of 3,817.

Subsequent analysis indicated that, as expected, the primary predictors were all related to video engagement levels, with video view count, like count, share count, and download count accounting for nearly all predictive signal in the data. With these results, we can conclude that videos with higher user engagement levels were much more likely to be claims. In fact, no opinion video had more than 10,000 views.
