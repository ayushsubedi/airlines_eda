# Preliminary Literature Review

## A Data Mining Approach to Flight Arrival Delay Prediction for American Airline

(a) the main idea
- American Airlines delays prediction using Gradient Boosting Classifer covering the top five US airports.

(b) why (or why not) it will be useful for your project
- The accuracy acheived using Gradient Boosting Classifier is 85.73%. This can serve us as a baseline as we explore other classification algorithms.  Additionally, this paper explores sampling techniques (such as R-SMOTE) to handle imbalance in classes. A similar strategy is required in our case as well.

(c) its potential shortcomings, that you will try to improve upon
- A more scientific/data-driven approach on feature selection might lead to a greater accuracy score. Similarly, XGboost, Deep Learning algorithm and other classification algorithms might lead to better classifier. Our dataset has more features and more data points. We also intend to perform dimensionality reduction, clustering and regression. 

## Systemic delay propogation in the US airport network

(a) the main idea
- The paper studies technical, operational or meteorological issues propogating delays across the US airport network. The paper also establishes passenger and crew connectivity as the most relevant factor for delay spreading. 

(b) why (or why not) it will be useful for your project
- We intend to study the cascading failures as delays in one airport create delays in others, and therefore the ideas laid here are relevant to us. 

(c) its potential shortcomings, that you will try to improve upon
- The paper establises passenger and crew connectivity as the most relevant factor for delay spreading. However, the paper only limits itself to 2010. We want to explore if this is relevant in the recent years (and during Covid) as well.

## Flight delay prediction from spatial and temporal perspective

(a) the main idea
- The paper proposes a novel Spatial Temporal Random Forest for flight delay prediction on China domestic flights between June and August, 2016 samples.

(b) why (or why not) it will be useful for your project
- We intend to experiment with some aspects of prediction on a spatial and temporal level within the different airports in the United States. This paper presents and effective approach.   

(c) its potential shortcomings, that you will try to improve upon
- NA 
