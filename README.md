# Fake_News_Detection
##Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.

The intended application of the project is for use in applying visibility weights in social media. Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.

## Description
This project proposes a methodology to create a model that will detect if an article is authentic or fake based on its words,phrases,etc. Applying supervised machine learning algorithms to an annotated dataset that is manually classified and secured.
Then, feature selection
methods are applied to experiment and choose the best fit features to obtain the highest precision,
according to confusion matrix results. We propose to create the model using different classification
algorithms. The product model will test the unseen data, the results will be plotted, and accordingly, the
product will be a model that detects and classifies fake articles and can be used and integrated with any
system for future use.
![I-Newspaper2](https://user-images.githubusercontent.com/84714153/217044993-8abe675e-f879-405e-af2e-9a740dd2f376.jpg)

## Algorithms Used:
  a. Logistic Regression
  b. Decision Tree Classification
  c. Gradient Boosting Classifier
  d. Random Forest Classifier
  
 ## Fake Detector Model
 ![image](https://user-images.githubusercontent.com/84714153/217046251-8de227d4-02b4-45d5-866f-57821456a7d6.png)

## Data Description:
train.csv -> Dataset used

## Result:
![image](https://user-images.githubusercontent.com/84714153/217047383-2adebe11-f9d7-4b70-b68d-3eace3143a0e.png)
