# Abuse_word_detect
In this article, we will build the Hate speech detection project in Python.

Hate speech detection is the model which identifies and detects the hateful and offensive speech being poured on the internet. Social media is a place for many people to make hateful and offensive comments about others. 

Before moving into the implementation part directly, let us get an insight into the steps in building a Hate Speech detection project with Python.

Steps in building Hate Speech detection using Machine Learning

Set up the development environment
Understand the data
Import the required libraries
Preprocess the data
Split the data
Build the model
Evaluate the results


Setting up the development environment
The first major step is to set up the development environment for building a Hate Speech detection project with Python. 
For developing a Hate Speech detection project you can use Google Colab https://colab.research.google.com/ for developing this project.

Understanding the data
The dataset for building our hate speech detection model is available on www.kaggle.com. 
The dataset consists of Twitter hate speech detection data, used to research hate-speech detection. 
The text in the data is classified as hate speech, offensive language, and neither. 
Due to the nature of the study, it’s important to note that this dataset contains text that can be considered racist, sexist, homophobic, or generally offensive.

There are 7 columns in our hate speech detection dataset:
index – This column has the index value
count– It has the number of users who coded each tweet
hate_speech – This column has the number of users who judged the tweet to be hate speech
offensive_language – It has the number of users who judged the tweet to be offensive
neither – This has the number of users who judged the tweet to be neither offensive nor non-offensive
class – it has a class label for the majority of the users, in which 0 denotes hate speech, 1 means offensive language and 2 denotes neither of them.
tweet – This column has the text tweet.

Importing the required libraries

We are going to import NLTK( The Natural Language Toolkit) library, used for symbolic and statistical natural language processing 
for English written in the Python programming language.

After importing the required libraries, it is time to load the data in our project.

Preprocessing the data
In Data preprocessing, we prepare the raw data and make it suitable for a machine learning model. 
When creating a machine learning project, it is not always a case that we come across clean and formatted data. 
And while doing any operation with data, it is mandatory to clean it and put it in a formatted way. 

We have used two important Natural Language processing terms, stopword and stemmer. 
Stopwords are the useless words (data), in natural language processing. We can avoid those words from the input. 
Stemming is the process of producing morphological variants of a root word. We have to find the stem word for each text better and easy prediction.

Splitting the data
The next important step is to explore the dataset and divide the dataset into training and testing data.

Building the model
After segregating the data, our next work is to find a good algorithm suited for our model. 
We can use a Decision tree classifier for building the Hate Speech detection project. 
Decision Trees are a type of Supervised Machine Learning used mainly for classification problems.

Evaluating the results
The final step in machine learning model building is prediction. 
In this step, we can measure how well our model performs for the test input.

Testing the model

#Accuracy Score of our model

We can infer that our model for Hate speech detection performs with an accuracy of 87 percent.

#Predicting the outcome

