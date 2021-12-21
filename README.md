# Detecting-Fake-News-with-Natural-Language-Processing
We will focus on text-based news and attempt to develop a model that will assist us in determining if a certain piece of news is fake or not.

![image](https://user-images.githubusercontent.com/86415241/146892156-53b89e61-d995-46a2-98b6-471daf3a63cc.png)


## Approach 
1. Data collection:Data collection is the process of obtaining information from a variety of sources in order to solve a specific research challenge. This data is saved in a file called a dataset and is subjected to various processes such as testing and evaluation.
2. Data Cleaning: Errors in the gathered data should be identified and corrected. This procedure is performed primarily to increase the dataset's quality, reliability, and accuracy of decision-making processes.
3. Data Exploration/Analysis:The process of tuning a dataset using one or more machine learning algorithms to match it to a business need, predict, or validate it.
4. Data Validation: The procedure for fine-tuning hyperparameters before running the model. This allows for an independent evaluation of a model fit on the training dataset.
5. Prediction on test data
## Usage

- Just run `jupyter notebook` in terminal and it will run in your browser.

  Install Jupyter [here](http://jupyter.readthedocs.io/en/latest/install.html) i've you haven't.

- install NLTK by using `pip install nltk` in command line prompt/ anconda  i've you haven't.

## Modules needed:
```
- nltk
- re
- Pandas
- numpy
- Scikit-Learn &
- seaborn
```
## Model Evaluation:
[[4558                     238]

 [  89                    4206]]
 
 Accuracy of the model is : 0.964030359696403
              precision    recall  f1-score   support

           0       0.98      0.95      0.97      4796
           1       0.95      0.98      0.96      4295

    accuracy                           0.96      9091
   macro avg       0.96      0.96      0.96      9091
weighted avg       0.96      0.96      0.96      9091

- As you can see, our Precision, Recall, and F1 Score are all excellent. As a result, we can confidently state that our model performs admirably on unobserved data. The accuracy score on the Test Dataset is 96.5%, which is excellent.

## About file:
- fake news dataset:https://github.com/rahkum96/Detecting-Fake-News-with-Natural-Language-Processing/blob/main/Fake_News.xlsx
- real news dataset:https://github.com/rahkum96/Detecting-Fake-News-with-Natural-Language-Processing/blob/main/Real_News.xlsx

