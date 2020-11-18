# Emotion Detection From President Donald Trump’s Tweets

## Team Members:
* Xiaohan Jiang
* Swapnil Parihar
* Pranav Karmalkar

## Primary Notebook:
256_project_v2.0.ipynb is the primary notebook for the project. 

## About the project:
In this paper, we apply emotion detection and quantification to US President Donald Trump’s tweets texts. President Trump updates his Twitter daily and presents opinions on various social topics. We are curious about the underlying emotions of his tweets. Analyzing and classifying text on the basis of emotions is a big challenge and can be considered as an advanced form of Sentiment Analysis. This paper proposes a method to classify text into five different Emotion-Categories: Happy, Angry, Surprise, Sad, and Fear. Python’s text2emotion library provides similar functionality but proved ineffective in handling negation and utilizing a person-specific vocabulary-emotion connection. Using this library as a fundamental algorithm, an improved algorithm was designed to achieve higher accuracy and faster running time. We customized an emotion-word dictionary for Trump tweet analysis goals, implemented negation checking, and selective word replacement. We have also successfully devised a method to visualize emotion distribution based on topic modeling. Moreover, we have tested our model in many circumstances: Trump’s retweet / deleted / election days tweets. All these testings showed that our model provides significant accuracy in classifying tweets taken from Trump’s tweets. After the successful implementation of our customized text2emotion algorithm, we implemented Named Entity Recognition(NER) using the BERT algorithm. Using NER we extracted locations from the tweets and using one-hot encoding we added the locations to the corresponding tweets. In case a new tweet is added we apply NER on it and extract the locations from this tweet. Then do time series analysis with respect to emotions on this tweet with respect to corresponding locations extracted.


