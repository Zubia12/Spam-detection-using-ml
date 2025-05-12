# Spam-detection-using-ml
Spam email detection is essential to ensure effective and safe communication system. This work 
investigates how machine learning algorithms for spam detection were implemented and 
evaluated, and analyses methods to improve accuracy and precision given the objective of various 
preprocessing and feature engineering scenarios. Logistic Regression, Support Vector Classifier 
(SVC), Multinomial Naive Bayes, K-Nearest Neighbors (KNN), AdaBoost, and Bagging 
Classifier models are all assessed. In fact, the dataset was extremely processed til the point to 
achieve optimal performance, preprocessing steps included TF IDF vectorization of the text, 
feature scaling, as well as addition of some more additional features such as the number of the 
characters in an email. The goal of this thesis was to train and test each model across these 
configurations to gauge the adaptability and effectiveness of each model in the task of spam versus 
legitimate email classification.   
The results show that Multinomial Naïve Bayes is the best algorithm, having perfect precision 
(1.000) in several configurations, and best accuracy (0.979) in feature scaling. We observed that 
Logistic Regression to have robust and consistent performance, achieving a precision of 0.971 
with the "Num Characters" feature, 0.967 with the scaling applied, hence it is a strong candidate 
for reliable spam detection. As far as the baseline performance is concerned, both SVC and 
AdaBoost are very strong, but SVC fares poorly with numeric features and yet AdaBoost shows 
reasonably accurare and precise training, regardless of scenario.   
To emphasize, the suitability of the tailored preprocessing techniques along with model selection 
in the context of a spam detection system is underscored in this research. This research enables the 
identification of Multinomial Naive Bayes as the most effective model to provide improvement 
over email filtering systems' precision and reliability. In addition, it showcases the significance of 
Logistic Regression on situations where stability and consistence performance is a must, hence 
presenting it as an option for robust spam detection implementation.   
