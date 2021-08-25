# NMA_DL
This is NLP group project result which was made during the NMA DL course: https://deeplearning.neuromatch.io/tutorials/intro.html

In this work, we implemented a model that predicts the sentiment of short text on a 1-5 scale across multiple topic domains with reasonably high accuracy. 
We used the Amazon Review Data 2018 dataset to train and test our model. 
The model consists of 2 parts: (i) a pre-trained BERT (Bidirectional Encoder Representations from Transformers) model that provides sentence embedding and (ii) a custom linear layer that estimates the sentiment ranking on the 1-5 scale.
Despite the limitations of a balanced dataset, results are promising as the model performed well when classifying product review text from other domains.
Future research should consider use of a larger dataset; application of various neural net models such as GPT-2, GPT-3 or implementation of meta-learning. 
