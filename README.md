# Twitter Sentiment Analysis of US Airlines

## Sentiment Analysis has been done using,
- VADER Lexicon
- TextBlob
- Machine Learning Models
- Word Embeddings

## About the Dataset: 
Source: Crowflower Data for Everyone
Twitter data was scraped from February 2015, the tweets are classified into positive, negative & neutral emotions

## Insights from the Data:
### - Sentiment Distribution Analysis
63% of the tweets are negative, whereas 21% positive & 16% neutral
![Sentiment Distribution](https://user-images.githubusercontent.com/47745543/83969424-93496e00-a8ed-11ea-8f3b-07bf7f5e1470.JPG)

### - Analysis of Airlines mentioned in the tweets
United Airlines followed by U.S Airlines have the highest tweet mentions
![Airlines listed](https://user-images.githubusercontent.com/47745543/83969434-a8be9800-a8ed-11ea-856f-9b812506804f.JPG)

### - Analysis of Top 10 Tweet Locations
New York location has the highest tweet mentions
![Tweet Locations](https://user-images.githubusercontent.com/47745543/83969445-b6741d80-a8ed-11ea-94c2-4803078427d6.JPG)

### - Analysis of User Time-zones
Eastern time followed by Central time are the timezones of most users
![User Timezones](https://user-images.githubusercontent.com/47745543/83969457-c3910c80-a8ed-11ea-85a9-c1bbb0cd93c7.JPG)

### - Word Cloud 
![Overall Word Cloud](https://user-images.githubusercontent.com/47745543/83969468-d1469200-a8ed-11ea-8f0a-d523449b0d28.JPG)

### - Word Cloud of Positive Reviews
![Pos Word Cloud](https://user-images.githubusercontent.com/47745543/83969477-ddcaea80-a8ed-11ea-9f0c-7a0035ee65f4.JPG)

### - Word Cloud of Negative Reviews
![Neg Word Cloud](https://user-images.githubusercontent.com/47745543/83969483-ecb19d00-a8ed-11ea-98ea-c148bc905539.JPG)

### - Analysis of Negative Reasons stated in the Negative Tweets
![Top Negative Reasons](https://user-images.githubusercontent.com/47745543/83969490-f9ce8c00-a8ed-11ea-9888-c2f2dd0fedda.JPG)

### - Top 15 Unigrams
![15 unigrams](https://user-images.githubusercontent.com/47745543/83969501-06eb7b00-a8ee-11ea-9586-e373cc856aa2.JPG)

### - Top 25 Bigrams
![25 bigrams](https://user-images.githubusercontent.com/47745543/83969510-14a10080-a8ee-11ea-87d3-e9ca4d679cf6.JPG)

### -Top 25 Trigrams
![25 Trigrams](https://user-images.githubusercontent.com/47745543/83969522-22ef1c80-a8ee-11ea-8cf1-217bb62a9b6b.JPG)

### Results of VADER Sentiment Analysis
Accuracy of VADER Lexicon is 49.61%

### Results of TextBlob Analysis
Accuracy of TextBlob is 42.91%

### Results of Machine Learning Models 
![ml models results](https://user-images.githubusercontent.com/47745543/83969534-31d5cf00-a8ee-11ea-9346-c0d71ae1f823.JPG)
![BOW ML Models Comparison](https://user-images.githubusercontent.com/47745543/83969547-3f8b5480-a8ee-11ea-84fe-0176f51d8bad.JPG)

### Results of Word Embeddings (word2vec) Sentiment Analysis
![word embedding result](https://user-images.githubusercontent.com/47745543/83969559-4d40da00-a8ee-11ea-9032-f941d7b52c8e.JPG)
![Word_Embedding ML Models](https://user-images.githubusercontent.com/47745543/83969567-5631ab80-a8ee-11ea-82d9-e6cca953e0de.JPG)

### Inference:
The following models have the best performance
- Sentiment Analysis with Logistic Regression gives 78% accuracy & 0.77 AUC-ROC Value 
- Word Embeddings with Gradient or XG Boost are good classifiers with 77% accuracy & 0.73 AUC-ROC Score
 


