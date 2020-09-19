# Quora Question Pair Similarity

<img src="/Images/quora.png" align="left" >

<p>Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.</p>
<p>
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.
</p>
<br>
> Credits: Kaggle, Top kaggler's solutions <br>
> Dataset: https://www.kaggle.com/c/quora-question-pairs <br> <br>


### Problem Statement 
- Identify which questions asked on Quora are duplicates of questions that have already been asked. 
- This could be useful to instantly provide answers to questions that have already been answered. 
- We are tasked with predicting whether a pair of questions are duplicates or not.

<br>

## 1.Quora
we do some Problem Understanding and then some basic Data Analysis followed by Feature extraction.

## 2.Quora_preprocessing
As the name suggests we do some data cleaning and then Crate new Features.

## 3.Q_Mean_W2V
Here we take a tf-idf (term frequency - inverse term frequency ) weighted Word2Vec using a Glove model.

## 4.ML_models
Finally we train our model on the refined dataset and get our results and evaluate them. You could further do Feture engineering and use more algorithms.
Even Deep Learning if you wish so.

### "Using Tensorflow" contains a very basic implementation of a neural network

### Final accuracy achieved was around 82 percent considering the incresease in True positives by about 0.4.

## Some advanced concepts that I learned
- How to do advanced feature engineering <br>
- How to do problem related researcch and study <br>
- Parallizing tasks for better performance

<br>

Enjoy !!
