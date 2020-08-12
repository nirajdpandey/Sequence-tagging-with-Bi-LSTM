# Sequence-tagging-with-Bi-LSTM
In this project, we will implement a Bi-LSTM architecture with Keras to perform part-of-speech tagging (a
sequence tagging task)

***
We use a subset of the data from the CoNLL-2003 shared task on Named Entity Recognition (provided in
`data` folder. It is pre-partioned into a training, development and test set.
The dataset consists of pre-tokenized sentences where every token is annotated with a part-of-speech tag,
a syntactic chunk tag and a named entity tag. In this project, we only use the part-of-speech tag.

*** 
One can set different parameters in the end of `main.py` to achieve better accuracy. With current default model architecture we are able to get 70% F1 score. Feel free to play with network architecture. 

