# ECommerce_Text_Unsupervised
DTSA 5510 Unsupervised Learning Final Project

Project Overview
This project will use unsupervised methods to group textual product descriptions from E-commerce websites. The data are from this Kaggle dataset: https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification . The data are all labeled with 4 classes: "Electronics", "Household", "Books" and "Clothing & Accessories". So the dataset is suitable for a supervised multiclass classification task. However we will apply unsupervised clustering methods to see how well we can group the text descriptions into the appropriate product categories. We will compare these results to supervised methods on the same data set.

Project Organization
The github repository for this project is located here:

https://github.com/albert-kepner/ECommerce_Text_Unsupervised

This project is organized as 4 separate notebooks. We tried two unsupervised approaches and two supervised approaches to separate product descriptions using the same dataset. This is an NLP problem because the data are unstructured English text product descriptions.

The four notebooks are in the github project with these direct links:

Model_1 ECommerce_Text_Unsupervised_NMF
https://github.com/albert-kepner/ECommerce_Text_Unsupervised/blob/master/ECommerce_Text_Unsupervised_NMF.ipynb

Model 2 ECommerce_SVD_KMeans_Unsupervised
https://github.com/albert-kepner/ECommerce_Text_Unsupervised/blob/master/ECommerce_SVD_KMeans_Unsupervised.ipynb

Model 3 ECommerce_TFIDF_XGBoost_Supervised
https://github.com/albert-kepner/ECommerce_Text_Unsupervised/blob/master/Ecommerce_TFIDF_XGBoost_Supervised.ipynb

Model 4 ECommerce_GloVe_LSTM_Supervised
https://github.com/albert-kepner/ECommerce_Text_Unsupervised/blob/master/ECommerce_GLOVE_LSTM_Supervised.ipynb