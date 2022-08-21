## Zodiac-Gender-Prediction

Dating applications are popular these days and OKCupid is one of them – getting information of users' preferences and trying to match couples. 

Dating apps also have a huge number of fake account or accounts with less details about themselves. So knowing a persons correct gender is usually useful.

In exception of general information, some users believe that zodiac signs may be a good signal to indicate whether they can get along with another user given zodiac sign. However, some users do not mind about identifying their signs in their profiles. The initial goal of this project is to create a model that can predict signs for users who do not inform them.

To predict a sign, this project used MultinomialNB. The model's F1-score is about 31%, respectively on training data. Unfortunately, after cross-validation, the accuracy of these four models are very low at about 3-8%. This predcition was done using scikit-learn's tfidfvectorizer and the columns used were essay columns. 

To predict the gender, Logistic Regression, KNN and Decision trees were used. The models' accuracies were 84.6, 85.4 and 85.7 respectively. This prediction was done using the columns body_type,	drinks,	drugs, education,	ethnicity, job,	location,	orientation, sign, smokes, speaks, status,
