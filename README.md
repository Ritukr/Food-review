
In this case study  using different machine learning techiques i try to solved  a text classification problem.
Dataset link => https://www.kaggle.com/snap/amazon-fine-food-reviews

Folder Descrptions:

1. Exploratory Analysis and Cleaning Data:
Here in this section , with help of  Jupyter Notebook I perform some tasks like reading the data, exploratory data analysis, data cleaning, etc.
 In this file i creaed two pickles files namely "final.sqlite" and "list_of_sent_for_input_to_w2v.pkl" which are used in the susequent folders.

2. KNN:
In this section I use K-Nearest Neighbors classifiers to classify the food reviews using 2 different featurizations namely "Bag of Words", "Word to vec", hence I have 2 different Jupyter Notebooks.

3. Naive Bayes:
In this folder, I apply Naive Bayes algorithm using Bag of Words featurization of the text; with and without Upsampling of the dataset, hence the two Notebooks.

4. Logistic Regression:
In this folder I apply Logistic Regression using Bag of Words and Word to Vec featuerization of the text.
Through different featurizations (Bag of Words, Word to Vec 100 dimensions, Word to Vec 200 dimensions), it can be concluded that Linear models tend to perform well if the dimensionality of the data is high.
