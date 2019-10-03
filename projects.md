---
layout: page
title: My Projects
---

|1. [Taxi demand prediction](../project_files/case_study_2.html)|
--------------------------|----------------------------
| Can we predict with reasonable accuracy, the number of taxis that need to be present at location **`l`** at time **`t`**? In this project, I've tried to give a solution to this problem using the [New York Taxis data](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml), with some time series analysis, basic statistics and some machine learning. I was able to achieve a satisfactory error of ~10%.|

|2. [Personalized Medicine: Redefining Cancer Treatment](../project_files/case_study_1.html)|
--------------------------|----------------------------
| A cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). This is my attempt at solving the kaggle problem described [here](https://www.kaggle.com/c/msk-redefining-cancer-treatment/). I was able to achieve an accuracy of **98.68%** and a `logloss` of **0.0643.**|

|3. [Stack Overflow Tag prediction](../project_files/sotp.html)|
--------------------------|----------------------------
| The task is to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title. The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions. You can find the kaggle problem [here](https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction).|

|4. [Microsoft Malware Classification challenge](../project_files/malware_detection.html)|
--------------------------|----------------------------
| This is my attempt at solving the Microsoft Malware classification challenge described [here](https://www.kaggle.com/c/microsoft-malware-prediction). I was able to achieve a logloss of **0.013** for this problem, which can be considered quite good. This problem was particularly interesting because it required me to deal with a huge amount of data, approximately 200GB.|

|5. [Quora Question Pair Chellenge - Identify duplicates](../project_files/quora_question_pair.html)|
--------------------------|----------------------------
| This competition was posted on Kaggle by Quora. The challenge is to tackle a natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. You can find this problem on Kaggle [here](https://www.kaggle.com/c/quora-question-pairs).|

|6. [Facebook Friend Recommender](../project_files/FB_Friend_Recommender.html)|
--------------------------|----------------------------
| Facebook, as everyone knows, is the biggest online social network in existance with Billions of daily active users. A friend recommender/account to follow is a very crucial problem to solve for a social network. In this project, I've tried to build a few models which predict whether one node (user) follows another. The results obtained were exciting, with the best f1 score of **0.92** on test data. You can find the original problem [here](https://www.kaggle.com/c/FacebookRecruiting/overview).|

|7. [Using LSTM to predict approved projects on DonorsChoose.com](../project_files/donors_choose_LSTM.html)|
--------------------------|----------------------------
| DonorsChoose.com is an online portal that empowers public school teachers in the USA to acquire funding for students' school projects. The donors who want to contribute can browse through hundreds of projects on the site to select the one they want to donate to. The site receives thousands of project requests to be posted on the site. Not every project is accepted. There's a manual review process. The problem faced here is to automate the review process by designing an ML model that can accurately predict whether a project would be approved or rejected.  [here](https://www.kaggle.com/donorschoose/io) is the full problem description on Kaggle.|

|8. Amazon Fine Food Reviews|
--------------------------|----------------------------
|  The "Amazon Fine Food Reviews" is a dataset that contains customer reviews collected for more than 10 years by Amazon. The objective of this project is to classify the reviews as positive or negative. I've tried various ML techniques for this which are listed below. You can find the original dataset [here](https://www.kaggle.com/snap/amazon-fine-food-review).

* [Logistic Regression](../project_files/afr_lr.html)

* [Support Vector Machines](../project_files/afr_svm.html)

* [Decision Trees](../project_files/afr_dt.html)

* [Naive Bayes](../project_files/nb.html)

* [Random Forests](../project_files/afr_rf.html)

* [Gradient Boosted Trees](../project_files/afr_gbdt.html)

* [Agglomerative Clustering](../project_files/afr_agg.html)

* [DBSCAN](../project_files/afr_dbscan.html)

* [KMEANS](../project_files/afr_kmeans.html)

* [tSNE](../project_files/afr_tsne.html)



|7. Random Stuff|
--------------------------|----------------------------
| This section contains some independent or ad hoc code I've written to try some experiments or improve my understanding of a topic.|

* [Predicting the outcome of a Cricket game](../project_files/Cricket.html)
	- This was actually a problem statement given to me in an interview. The requirement was to just draw a flow chart to explain the approach. I expanded the scope of it and used an actual dataset available on Kaggle to demonstrate some EDA and ML.

* [Exploratory Analysis on Haberman's dataset](../project_files/hb.html)

* [Implementing Gradient Descent](../project_files/gd_1.html)
	- Implemented the Gradient Descent algorithm to perform Linear Regression.

* [Statistical Analysis using Python](../project_files/statistics.html)
	- Basic statistics using Python to understand distributions of data, and Hypothesis testing.

* [Mammographic Masses Classification](../project_files/mammographic_masses_classification.html)
	- This problem is similar to the tumor classification challenge described above, but having a smaller scope. The data for this problem is taken from the [UCI ML repository](http://archive.ics.uci.edu/ml/datasets/mammographic+mass).

* [Word vectors using Truncated SVD](../project_files/random/Word_Vectors_using_Truncated_SVD.html)

* My journey into understanding **_Neural Networks_**
	- [A very simple Neural Network to get started](../project_files/dl/simplest_nn.html)
	- [Predicting house price using a simple Neural Network](../project_files/dl/house_price.html)
	- The Hello world of Neural Nets - MNIST
		- [Multilayered Perceptron](../project_files/dl/mnist.html)
		- [Using a ConvNet](../project_files/dl/mnist_cnn.html)
		- [Fasion MNIST](../project_files/dl/fasion_mnist.html)




