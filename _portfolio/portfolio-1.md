---
title: "Automated Hate Speech and Oﬀensive Language Detection"
excerpt: ""
collection: portfolio
---


•	Developed a bag of words model to detect and classify hate speech and offensive speech on Twitter to help monitor and filter out extreme tweets more efficiently based on the model. 
•	Applied our classiﬁcation model to real world data by drawing thousands of tweets through Twitter API. Successfully filtered out over 95% of the benign class and retrieve over 60% of the tweets that contain hate language.


[Automated Hate Speech and Oﬀensive Language Detection](http://yueqiusun.github.io/files/Automated Hate Speech and Oﬀensive Language Detection.pdf)


We try to build a classifier to help administration to monitor and filter out tweets with extreme language more efficiently. We train the classifier based on the labeled data on the Github. The data contains 24000 tweets and the labels corresponding to each tweet. The label is either "the tweet contain hate language" or "the tweet don't contain hate language but contain offensive language" or "the tweet contain neither". In the data preparation part, we 

Steps of processing tweet data:

• Remove URLs and emoij using regular expressions

• Tokenize text based on space characters and convert words into lowercase

• Remove words beginning with Mention (@)

• Convert contractions to formal writing based on a dictionary we build, and then remove punctuations

• Remove words with length less than 2 and words that are not alphabetic

• Remove stop words. For the stop word list, add some common words in tweets, like ’rt’ and ’ﬀ’, and remove negation words which may be important in bigram features.

• Stem and lemmatize words to convert inﬂectional forms and derivational forms of words to base forms. In terms of extracting features, we can choose n-gram, like unigram and bigram, and diﬀerent modes including TFIDF, count and binary. Besides, we can use parts of speech of each word in the same way. We also take advantage of some other features. First, there are some statistics of text including the number of words, characters, syllabus, URLs, hashtags and mentions; second, Flesch-Kincaid grade level and Flesch readability ease both are used to measure readability of text; third, sentiment analysis indicators based on VADER are used to evaluate how positive or negative a piece of text is.




