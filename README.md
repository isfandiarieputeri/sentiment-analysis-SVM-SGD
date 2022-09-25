# sentiment-analysis-SVM-SGD
This is my thesis for my undergraduate program, it's about Sentiment Analysis using one of the most popular machine learning methods Support Vector Machine (SVM) modified by Stochastic Gradient Descent (SGD). Because the data used here is raw data and the data type is text data, so this code contains the text preprocessing too. In this thesis, I used two different text representations including Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF). The machine learning methods I used in this thesis are SVM and SGD-SVM. So, this code will provide two different machine learning methods with two different text representation methods.

The dataset I used here is the review of PeduliLindungi app on Google Play on January 2022 (in Bahasa Indonesia). I got the data by web scraping using google_play_scraper. This dataset is imbalanced data, so this code will contain how to deal with the imbalanced data too.

To maximize the performance of the machine learning methods, I do Hyperparameter Tuning in order to find the best Hyperparameter so that machine can run its best.
