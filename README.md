# Hotel-Booking-cancellations-prediction

* Data cleaning
* EDA
* Machine learning model building

In the hotel industry, when there are last-minute booking cancellations or ‘no shows’, it affects the income of the hotel badly resulting in the hotel employing vigorous cancellation policies and overbooking strategies. However, these have a negative impact on the number of bookings. This problem can be minimized by developing a machine-learning model that could accurately predict booking cancellations. The dataset was obtained through Kaggle which included hotel booking data relating to two hotels in Portugal. The data was cleaned, analysed and visualized using Python. 

Commonly used machine learning binary classification models namely; Logistic Regression, Decision Tree Classifier, Random Forest Classifier, K-Nearest Neighbors and Bernoulli Naive Bayes were tested. According to the evaluation metrics; accuracy, precision, recall, F1-score and ROC AUC, Random Forest Classifier performed the best obtaining an accuracy score of 85%. 

As per the results obtained through correlation coefficients, the top scores of the chi-squared test and the top features from feature importance, the key factors which influenced booking cancellations were identified as follows;  the lead time, the number of previous cancellations made, total number of special requests made to a booking, the number of car park spaces available, the number of changes made to a booking, the guest being a repeated guest or not, the average daily rate and the type of customer. By discovering these factors, hotels will be able to identify booking patterns better and modify their cancellation policies and overbooking strategies according to the attributes of the booking.
