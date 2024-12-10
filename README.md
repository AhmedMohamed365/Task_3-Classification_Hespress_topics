# Task_3-Classification_Hespress_topics
 Classifying new articles to their corresponding topic value

 Task 1 - spell checker : 
 
 https://github.com/AhmedMohamed365/Task1-spellingChecker
 
 Task 2 - exploratory data analysis of the data : 
 
https://github.com/AhmedMohamed365/Task-2-EDA_Hespress_Dataset

 The training was done by :
 * Preprocessing data ( removing stop words , stemming).
 * Normalizing text by removing different diacritics.
 * Encoding Target column (topic ) using label encoder.
 * Embedding of Text using Tf-idf vectorizer to extract features.
 * PCA for dimension reduction
 * Hyperparameter tuning using a grid search
 * Evaluating model using cross validation
 * Trained different classifiers like xgboost , randomForest, SVM, Decision Tree

Naive Bayes got the best accuracy 

![image](https://github.com/AhmedMohamed365/Task_3-Classification_Hespress_topics/assets/56398966/7fcba695-a1e3-4b76-8b0a-01d7943e0ba3)


other models maybe need more hyper parameter tuning and doing normalization for the data before feeding it to the model.



# Conclusion 
* We can improve accuracy by using deep neural network like multi-layer perceptron
* Transformer model like Bert
* Using a pre-trained model on bigger data 
* Using features like text length and the date of the story
* Hyper parameter fine-tuning
