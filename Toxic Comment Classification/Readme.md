# Toxic Comment Classification

Discussing things you care about can be difficult. 
The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. 
Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.


## Objective

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

 * toxic
 * severe_toxic
 * obscene
 * threat
 * insult
 * identity_hate <br>
 
You must create a model which predicts a probability of each type of toxicity for each comment.

## Data Sample

id | Comment Text | toxic | severe_toxic | obscene | threat | insult | identity_hate
------------ | ------------ | --------- | -----------| -----| -----| ------| ----
0000997932d777bf | Stupid peace of shit stop deleting my stuff idiot go die and fall in a hole go to hell! | 1 | 1 | 1 |0 |1 | 1

## My Approach
  * Clear the comment text data
  * find the comment length and number of words and extract as features
  * Vectorize the comment_text
  * Create mroe sample points using ```iblearn``` library
  * Use new sample distribution for training and old training distribustion without resampling as test
  * Compare the results with model trainind on raw training data vs resampled data

  
### Accuracy achieved = 98%
### mean columns wise ROC_AUC achieved = 94%

## In this project I learned different ways to deal with multilabel Data
