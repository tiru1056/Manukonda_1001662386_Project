## Project Title :- Personality Prediction of People Based on Social Media Posts
**Summary :-** The aim of this project is to build a system that helps in predicting individual's personality.

1.   Myers- Briggs Type Indicator (MBTI) is used to classify each indivdual into   different personality traits such as Introversion-Extroversion(I-E), iNtuition-Sensing(N-S), Feeling-Thinking(F-T) and Judging-Perceiving(J-P).
2.   Understanding the data from df, It has two columns with Indicator 'type' and the related'posts'
3.   Posts are used input and we need to predict the Indicator for the given posts
4. Start with preprocessing the input document,we need clean the Posts which includes removing stopwords, deleting the links, punctuation's, converting to lower.
5. We need to create seperate columns for each binary indicators of IE,NS,TF,JP
6. Visual the Ouput labels w.r.t each indicator
7. We can undertsand that Data is highly imbalanced in case of IE and NS, So we need to trying resampling methods 
8. Use Count Vectorizer to convert into numbers using frequency of each word in the list, and using Tfidf vectorizer convert to term ferquency matrix .
8. Lets start predicting by using classifier Logistic Regression, Decision Tree,RandomForest Classifier, Multinomial naive bayes classifier and XG Boost Classifier.
9. Looking at the classification reports, RandomForest Classifier performed better than other models.
10. Lets try resampling using Smote, Near Miss And RandomOversampling technique's
11. Suprisingly resampling haven't improved performance of the model
12. Summary of the Project and future scope of it

#### Open this file from the Google Colab by uploading the notebook or using from python commmand prompt command line 'jupyter notebook MLProject.ipynb ', using jupyter notebook
