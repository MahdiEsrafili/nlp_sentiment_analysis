# Sentiment Analysis
in this repo, a twitter dataset is going to analysed. dataset contains twitts and label of them. labels are "positiv, negative, neutral".
but there is a imbalance that neutral twitts are more than others and the negative sentences are least.
here i'm going to describe some things.

## preprocessing
1. removing stop words: stop words are those who has no special information and not important. but sometime this get important.
2. tokenize: 2.1: word tokenize: splitting a sentense to words 2.2: splitt a text to sentences. it creates list of tokenized objects.
3. lemmatize: converting verbs like "went, running" to "go, run".
