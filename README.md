# AD-click-prediction

# Problem Description:

Clickthrough rate (CTR) __ is a ratio showing how often people who see your ad end up clicking it. Clickthrough rate (CTR) can be used to gauge how well your keywords and ads are performing.

1. CTR is the number of clicks that your ad receives divided by the number of times your ad is shown: clicks ÷ impressions =     CTR. For example, if you had 5 clicks and 100 impressions, then your CTR would be 5%.

2. Each of your ads and keywords have their own CTRs that you can see listed in your account.

3. A high CTR is a good indication that users find your ads helpful and relevant. CTR also contributes to your keyword's     expected CTR, which is a component of Ad Rank. Note that a good CTR is relative to what you're advertising and on which networks.

    Credits: Google (https://support.google.com/adwords/answer/2615875?hl=en)

Search advertising has been one of the major revenue sources of the Internet industry for years. A key technology behind search advertising is to predict the click-through rate (pCTR) of ads, as the economic model behind search advertising requires pCTR values to rank ads and to price clicks. In this task, given the training instances derived from session logs of the Tencent proprietary search engine, soso.com, participants are expected to accurately predict the pCTR of ads in the testing instances.

## Useful Links:

1. Source : https://www.kaggle.com/c/kddcup2012-track2 

2. Dropbox Links __: https://www.dropbox.com/sh/k84z8y9n387ptjb/AAA8O8IDFsSRhOhaLfXVZcJwa?dl=0 

3. Blog :https://hivemall.incubator.apache.org/userguide/regression/kddcup12tr2dataset.html


## Real-world/Business Objectives and Constraints 

1. Objective: Predict the pClick (probability of click) as accurately as possible.

2. Constraints: Low latency, Interpretability.

## Type of Machine Learning Problem 

It is a regression problem as we predicting CTR = #clicks/#impressions

## Performance metric 

1. Souce : https://www.kaggle.com/c/kddcup2012-track2#Evaluation 
2. ROC
