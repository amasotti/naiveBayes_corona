# Naive Bayes classifier for Tweets

Example of a very simple Naive Bayes classifier trained on a dataset of [Tweets about the Covid19](https://www.kaggle.com/datatattle/covid-19-nlp-text-classification).
Implemented following the explanation in [Jurafksy & Martin](https://web.stanford.edu/~jurafsky/slp3/) (chap. 4).


The language model was smoothed using the simple Laplace (add-one) smoothing method.

## Requirements

+ `pandas`
+ `nltk` (including the TweetTokenizer in the subpackage nltk.tokenize)
+ `matplotlib`
+ `seaborn`
+ `tqdm` (for the progress bars)

