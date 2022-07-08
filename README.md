### Kaggle-nlp with disaster tweets
This is a tutorial in an IPython Notebook for the Kaggle competition, Natural Language Processing with Disaster Tweets. The goal of this repository is to provide an example of a competitive analysis for those interested in getting into the field of data analytics or using python for Kaggle's Data Science competitions.

**Quick Start:** [View](http://nbviewer.ipython.org/urls/raw.github.com/Mieczmik/nlp-with-disaster-tweets/main/nlp-with-disaster-tweets.ipynb) a static version of the notebook in the comfort of your own web browser.

### Installation:

To run this notebook interactively:

1. Download this repository in a zip file by clicking on this [link](https://github.com/Mieczmik/nlp-with-disaster-tweets/archive/master.zip) or execute this from the terminal:
`git clone https://github.com/Mieczmik/nlp-with-disaster-tweets.git`
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with `virtualenv env`.
4. Activate the environment with `source env/bin/activate`
5. Install the required dependencies with `pip install -r requirements.txt`.
6. Execute `ipython notebook` from the command line or terminal.
7. Click on `nlp-with-disaster-tweets.ipynb` on the IPython Notebook dasboard and enjoy!
8. When you're done deactivate the virtual environment with `deactivate`.


### Kaggle Competition | Titanic Machine Learning from Disaster

>"Twitter has become an important communication channel in times of emergency. 
> The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. 
> Because of this, more agencies are interested in programatically monitoring Twitter
> (i.e. disaster relief organizations and news agencies). 
> In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. 
> You’ll have access to a dataset of 10,000 tweets that were hand classified."
From the competition [homepage](https://www.kaggle.com/competitions/nlp-getting-started).

### Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python using a full complement of PyData utilities. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

#### This Notebook will show basic examples of:
#### Data Preprocessing
* Importing Data with Pandas
* Data Review
* Work with text data:
  + Tokenize tweets with TweetTokenizer
  + Remove numbers, punctuation and hashtags
  + Stemming words with PorterStemmer
  + Create pipelines with Tfidf or Count Vectorizers
#### Data Analysis
Training listed below machine learning models using GridSearchCV and Pipelines:
  + Naive Bayes Classifier
  + Linear Support Vector Classifier
  + Support Vector Classifier
  + Logistic Regression
  + k-Nearest Neighbors
  + Decission Tree Classifier
  + Random Forest
  + Bagging Classifier
  + Extra Trees Classifier
  + Adaptive Boosting (AdaBoost)
  + Gradient Boosting
  + Extreme Gradient Boosting (xgboost)
#### Summary
* Plotting results
* Export results


