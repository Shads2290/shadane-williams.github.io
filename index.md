# Shadane's Data Science Portfolio

Here are some of my best Data Science Projects. I have explored various machine-learning algorithms for different datasets. Feel free to contact me to learn more about my experience working with these projects.


***

[Examining the effect of environmental factors and weather on Bike rentals](https://colab.research.google.com/drive/1Ztd0YmzNaq-2tdpf-vsfw0iuIoFJcbvH#scrollTo=EeFTlfPDQfYx)

<img src="images/seoul-bikes.jpeg"/>

- Used Linear Regression to predict the number of bikes rented in the city of Seoul.
- After implementing sklearn.metrics it yeilded the following results:
- Mean Absolute Error of linear regression: 1.807283706047584e-13
- Mean Square Error of linear regression: 5.633155215223513e-26
- R_Squared Score of linear regression: 1.0
- In an effort to address overfitting I used Lasso Regression which had a training score 99.9%.

***

[Identifying Customers Likely to Subscribe for Term Deposit](https://colab.research.google.com/drive/1h3Rnc_h4cgTWTaLEYmQDgoLqIJdiNlsc)

<img src="images/bank.jpeg"/>

- Used logistic regression to identify potential bankers based on various attributes.
- Implemented SMOTE to balance class labels.
- Used Logistic regression classifier & optimized the accuracy by using the ROC curve.
- Created the confusion matrix for the predictions and make note of the outputs.
- Created a classification report and eplored the various outputs.
- Model had an accuracy score 90.1%.

***

[Identifying possible click fraud by legitimizing user atributes](https://colab.research.google.com/drive/1DYGea-2emPmFyuRSePx4v5Ibz7X3S74I#scrollTo=qi_Hh-BBfSiq)

<img src="images/click fraud.jpeg"/>

- Used the features associated with clicks, such as IP address, operating system, device type, time of click etc. to predict the probability of a click being fraud.
- Used the Random Forest, Bagging classifier, and XGBoost classifier.
- Used these three models to distinguige click fraud base on accuracy.
- Selected best model based on train and test performance.
- Random Forest, Bagging classifiers, and XGBoost models have an approximate accuracy of 99%. 

***

[Identifying symptoms of orthopedic patients as normal or abnormal](https://colab.research.google.com/drive/1NWqcJ_xf5tZ997tVXJxUFxfKbB8rOYx4#scrollTo=ym-y6CYpZVjy)

<img src= "images/bones.jpeg"/>

- Used the K Nearest Neighbours algorithm and Naive Bayes Classification to classify a patient's condition as normal or abnormal based on various orthopedic parameters.
- After examing the confusion matrix there was 51 correct predictions and 11 false predictions.
- Accuracy of the Naive Bayes Clasification is 82.26%. 
- The accuracy of KNN Model is 85.5 with K = 1.

***

[Identifying total compensation based on a vareity of benefits provided by the San Francisco Controller's Office](https://colab.research.google.com/drive/1r8buRPpTT-F009BI0mFsToJrf5bMYfdM#scrollTo=OWR6XNB4A5Gi)

<img src= "images/Total Compensation.jpeg"/>

- Used the K Nearest Neighbours algorithm to total compensation of employees on various atributes.
- Compared predictive performance by fitting a Naive Bayes model to the data.
- Selected best model based on train and test performance.
- Doing different comparisons showed that benefits are proportional to ones total compensation.
***

[Used PCA to identify most important atributes to accurately predict housing market](https://colab.research.google.com/drive/1qLA_6kUuqd9vT_KfFzq2qxQZp40XEuZh)

<img src= "images/housing.jpeg"/>

- Used principle component analysis to reduce non important atributes to better estimate house market value
- Scale data for best PCA consants without loss of information
- Found number of components with at least a 90% variance
***

[Using NLP to determine whether the review is positive or negative](https://colab.research.google.com/drive/1aoQel3nYgHOJAWllF-56BQdoG3xiV4fN)

<img src= "images/reviews.jpeg"/>

- Used the SQLite Table to read data
- Used HelpfulnessNumerator, set of stopwords, snowball stemmer and cleanpunc functions to prepare data for futher analysis
- Used the countvectorizer to train data and observe output. 
- The model showed the Best alpha Value 0.05 with highest roc_auc Score is 91.8%.

***

[Used CNN model to identify images between a dog or a cat](https://colab.research.google.com/drive/1rvMGRZg5jFbRNBBKpVkIrA-javVkPkKs)

<img src= "images/CATS.jpeg"/>

- Used convolution neuro network model to train a series of pictures of dogs and cats
- There are two convolution layers with relu activatioon with two pooling layers of 2x2 kernels with 2 step stride
  following the flattening stage.
- The full conection stage uses relu activation with a sigmoid output to hold within 0 to 1 boundaries
- Selected best parameters based on train and test performance using 20 epochs
- The model identifies dogs and cats with 83% accuracy

***

[Deep Neural Network with Keras for MNIST handwritten classification and recognition](https://colab.research.google.com/drive/1t7NiTczdrYY6BqL0umevKVKkr73Y8mUz)

<img src= "images/HAND.png"/>

- Developed a driver block to develop a working model and establish a few baseline architecture for a classification task.
- Improved the performance of the model through two different processes.
- Created a finalized model and then used it to create predictions on new images.
