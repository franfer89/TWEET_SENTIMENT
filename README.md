# TWEET SENTIMENT EXTRACTION

**Kaggle competition**: [Tweet Sentiment Extraction](https://www.kaggle.com/c/tweet-sentiment-extraction)

Several tweets are classified as neutral, positive or negative. The task consist in extracting which part of the tweet makes the tweet neutral, positive or negative.

**Example**

INPUT:

tweet sentence:"  SWEEEEET - San Fran is awesome!!!!  Love it there "

*it is known to be defined as positive*

OUTPUT:

it is positive because it contains: " Love it there "


**FILES**

*TS_20200508.ipynb*: contains a solution using glove.6B.100d and LSTM recurrent neural network

*Data/train.csv*: training data
*Data/test.csv*: test data

*glove.6B.100d.txt* can be downloaded from: [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)