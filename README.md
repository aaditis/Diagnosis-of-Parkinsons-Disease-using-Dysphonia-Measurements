# Diagnosis-of-Parkinsons-Disease-using-Dysphonia-Measurements

The goal of the study is to classify people suffering from PD from healthy people by using speech data. Various AI algorithms are used here because they can directly measure the extent to which people with PD can be discriminated from healthy controls which is difficult in cases of remote monitoring where there is more variation in measured features than under controlled conditions. A comparative study is carried out using various evaluation methods for calculating the performance of the classifiers. It has been scientifically proven that approximately 90% of patients with PD exhibit some form of vocal impairment, which is one of the earliest indicators. Thus, voice measurement to detect and track the progression of symptoms of PD has drawn significant attention. 

The dataset for this project consists of 195 sustained vowel phonations from 31 male and female subjects, of which 23 were diagnosed with PD. Averages of six phonations were recorded from each subject, ranging from one to 36 seconds in length [8]. Each column in the table is a voice measure, and each row corresponds to a recording from individuals. One of the columns defines ‘status’ which has binary values: 1 - people with PD (147 readings) and 0 - those who are healthy (48 readings).

The following data exploration techniques were implemented on the dataset:
1) Summary Statistics: Mean, Median, Range
2) Plotting: Histogram, Box Plot, Scatter Plot
3) Statistical Analysis: T-test, Heatmap
4) Unsupervised: K-means, Clustergram, Principal Component Analysis.

The dataset was divided into training data and testing data with 70% split and 30% split respectively for Logistic Regression, Decision Trees, Random Forest and Support Vector Machine, and 80% and 20% split for Neural Networks. The model was designed using cross-validation. The test data was evaluated based on average accuracy, precision, recall, confusion matrix, correlation, MAE.

<img width="461" alt="evaluationMetric" src="https://user-images.githubusercontent.com/73272667/111698052-befa6c80-880c-11eb-831e-37d75528b1e0.PNG">
