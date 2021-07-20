# Summer Analytics Capstone Project by C&A Club, IIT Guwahati

###Solution and Approach to the Build a machine learning model to estimate the revenue that will be generated through ads

Hosted at: https://dphi.tech/challenges/summer-analytics-capstone-project-by-ca-club-iit-guwahati/135/overview/evaluation

Rank: 36 from 711 registered participants.


### Problem Statement

An advertiser on the platform (DeltaX) would like to estimate the performance of their campaign in the future.
Imagine it is the first day of March and you are given the past performance data of ads between 1st August to 28th Feb. 
You are now tasked to predict an ad's future performance (revenue) between March 1st and March 15th. 
Well, it is now time for you to put on your problem-solving hats and start playing with the data provided under the "data" section.

### Data Description

- date: the date on which the ad was made live
- campaign: campaign number
- adgroup: adgroup number
- ad: ad number
- impressions - Number of time the ad was shown
- clicks - Number of time the ad clicked shown
- cost - Amount spent to show ad
- conversions - Number of transactions received
- revenue: revenue generated from the ad


### Evaluation Metric

The evaluation metric for this competition is Root Mean Squared Error (RMSE) value.

### Approach

- Solving it as a Regression problem.
- Feature Engineering
   1. Creating datetime features.
   2. Data Encoding.
   3. Feature Scaling.
- Building baseline models and tuning.

### Ranking

- Leaderboard Rank - 35
