# Detecting-Fake-News-with-Natural-Language-Processing
We will focus on text-based news and attempt to develop a model that will assist us in determining if a certain piece of news is fake or not.

![image](https://user-images.githubusercontent.com/86415241/146892156-53b89e61-d995-46a2-98b6-471daf3a63cc.png)

## About:
This task is organized by ByteDance, the Platinum Level Sponsor of the conference. ByteDanceis a global Internet technology company. Our goal is to build a global content platform that enable people to enjoy various content in various forms. We inform, entertain, and inspire
people across language, culture and geography.

One of the challenges which we are facing is to combat different types of fake news. Fake newshere refers to all forms of false, inaccurate or misleading information, which now poses a big threat to human civilization.

## Problem description: 
At Bytedance, we have created a large-scale database to store existing fake news articles. Any new article must go through a test on the truthfulness of content before
being published. We conduct matching between the new article and the articles in the database. Articles identified as containing fake news will be withdrawn after human verification. The accuracy and efficiency of the process, therefore, becomes crucial for us to make the platform safe, reliable, and healthy


## Approach 
1. Prepare the data: You’re provided with two excel dataset, first level them and merge those two
data into one.
2. Clean the data: Clean the data, that is, remove the duplicated news articles, remove special
characters, numbers etc., correct the spellings of words.
3. Conduct EDA (Exploratory Data Analysis) on the cleaned Data: Perform Unigram, Bigram and
Trigram analysis on both real and fake news. Create wordcloud on both data based on the subject.
Summarize the words and explore the data and then decide your strategy. Make note of any
important assumptions that you make.
4. Convert the text data: You have to transform each news article into a numerical representation to
create a machine learning model. For example, if we have defined our dictionary to have the
following words(predictors) {This, is, the, not, awesome, bad, basketball}, and we wanted to
transform the text “This is awesome” into a numerical representation, we would have the following
numerical representation of that text : (1, 1, 0, 0, 1, 0, 0).
5. Develop and Validate Samples: Divide converted data into 2 parts: Development Sample (70%) &
Validation Sample (30%). Build your analysis model using the Development Sample, and validate it
on the validation sample and then predict on test sample. You can use neural network to create a
model.
6. Improving model accuracy: Perform various iterations by eliminating or adding the
variables(words) to see if the model accuracy is improving or not.
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

 Accuracy of the model is : 0.964030359696403
             
             
                precision    recall  f1-score   support

           0       0.98      0.95      0.97      4796
           1       0.95      0.98      0.96      4295

    accuracy                           0.96      9091
   
- As you can see, our Precision, Recall, and F1 Score are all excellent. As a result, we can confidently state that our model performs admirably on unobserved data. The accuracy score on the Test Dataset is 96.5%, which is excellent.

## About file:
- fake news dataset:https://github.com/rahkum96/Detecting-Fake-News-with-Natural-Language-Processing/blob/main/Fake_News.xlsx
- real news dataset:https://github.com/rahkum96/Detecting-Fake-News-with-Natural-Language-Processing/blob/main/Real_News.xlsx

