# Text_Summarization_with_Tensorflow
patch-2
Implementation of a seq2seq model for summarization of textual data using the latest version of tensorflow. \
 patch-4
Demonstrated on Amazon Reviews, github issues and news articles. 

Demonstrated on amazon reviews, Github issues and news articles. 

Implementation of a Seq2seqmodel for Summarization of textual data using the latest version of tensorflow. \
Demonstrated on amazon reviews, github issues and news articles. 
master
master

## Prerequisites
- Tensorflow
- nltk
- numpy
- pandas 
- langdetect

## Datasets
I tried the network on three different datasets. 
1. Amazon Fine Food Reviews dataset
2. github issues dataset
3. all the news dataset

All Three of them are available on Kaggle:
- https://www.kaggle.com/snap/amazon-fine-food-reviews/data
- https://www.kaggle.com/davidshinn/github-issues
- https://www.kaggle.com/snapcrack/all-the-news

## Code 
I uploaded three **.py** and three **.ipynb** files. The .py files contain the network implementation and utilities. The notebooks are demos of how to apply the model. Maybe it is useful for someone.

## Architecture
**Seq2Seq model**
- Encoder-Decoder
- Bidirectional RNN
- Bahdanau Attention
- Adam Optimizer
- exponential or cyclic learning rate
- Beam Search or Greedy Decoding
--
