# E-Commerce-Colab

<h2>Motivation : </h2>In this digital world, there is a rapid increase in the e-commerce business and after COVID the demand for the e-commerce business has increased. As there is no interaction between seller and buyer, so the reviews are the only way the busniess would get to know about customer interest,satisfaction and for the new customers the reviews would help them to take decisions about buying.

<h2>Data Gathering:</h2>
Gathered the data from E_commerce website. 
<h2>Data Preprocessing and text preprocessing:</h2>(Null value ,stop words,special characters(punctuations,?......),lemmatization,word tokenization,pos tagging,preprocessed the words by updating the stop words
<h2>Insights: </h2>word cloud(gives insight about the most frequently occuring word),collinearity,relationship between different variables, provided insights using bigram analysis.
<h2>Sentiment Analysis:</h2>Used vader sentiment intensity analyzer to analze the sentiment of the reviews (pos,neg,neutral,compound). Based on compound we classified whether the review is a positive or negative.
<h2>Data partition:</h2random sampling of data (70-30)(train,valid,tech)

<h2>Feature engineering:</h2>Used count vectorizer, tfidf vectorizer for generating feature vector for words.
<h2>Classification model:</h2>
Developed a machine learning pipeline using count vectorizer, tfidf vectorizer,different models such as Bernoulli Naïve Bayers, SVC,Decision tree, logistic regression which classify the reviews in to recommended or not.
Built ensemble classifier using base classifiers, cross validation using  Kfold and obtained 88 percent accuaracy by mean of cross validation score.
