# Text-Classification
Dataset: 20 news_groups

# Pre-Processing
  The task is to classify a test document into one of the 20 news_groups.
  
  To achive that i have made a list of words that might help me in determining the group that it belongs to. I have removed a set of words called "STOPWORDS" which are the most common words from this list.
  This "Vocabulary" Dictionary contains all the 20 news_groups as keys, and the frequency of all important words as value.
  
  This Dictionary is used to select a the cut-off frequency, by using a plot. This cut_off Frequency removes all the words which have comparatively lower frequency.
  I have found the frequency to be "100".
  
  All the words above having frequency more than this cut-off are chosen as features for classification
  
  The Model is trained and tested on this feature matrix to acheive the accuracy as listed below.  
  
  #1 Implement inbuilt Multinomial Naive Bayes.
    Accuracy: 86.12%

  #2 Implement a Multinomial Naiye Bayes class from scratch
    Accuracy: 86.02%
    
  #Conclusion: The Multinomial Naive Bayes implemented from scratch shows accuracy very close to the inbuilt classifier.
  
