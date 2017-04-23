# sentiment-nlp
Demo of Sentiment analysis in Python

# Requirements
[Stanford CoreNLP]{http://stanfordnlp.github.io/CoreNLP/}
Python 2.7
pycorenlp - pip install pycorenlp

# How to run the code?
Start the Stanford CoreNLP server

> cd stanford-corenlp-full
> java -mx5g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -timeout 10000

Go to your source code directory

run the following command
python demo-sentiment.py
