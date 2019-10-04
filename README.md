
## IEEE CIS Fraud Detection Competition on Kaggle
## Context
IEEE-CIS works across a variety of AI and machine learning areas, including deep neural networks, fuzzy systems, evolutionary computation, and swarm intelligence. Today they’re partnering with the world’s leading payment service company, Vesta Corporation, seeking the best solutions for fraud prevention industry, and now you are invited to join the challenge.

In this competition, you’ll benchmark machine learning models on a challenging large-scale dataset. The data comes from Vesta's real-world e-commerce transactions and contains a wide range of features from device type to product features. You also have the opportunity to create new features to improve your results.

If successful, you’ll improve the efficacy of fraudulent transaction alerts for millions of people around the world, helping hundreds of thousands of businesses reduce their fraud loss and increase their revenue. And of course, you will save party people just like you the hassle of false positives.
## Describe your project

My submission was based on using recursive feature leimination to create feature selections and ranking before feeding it into a CatBoost model.
There is also code for CatBoost feature evaluation.
##Noisy Data
There was an outstanding question of a polluted dataset because since frauds can only be detected after the fact, running Elliptical Envelopes and Isolation Forests shows outliers in the data.
##Imbalanced Data
Having tried SMOTE, NearMiss, Tomeklinks and RandomUndersampler produced worse results
