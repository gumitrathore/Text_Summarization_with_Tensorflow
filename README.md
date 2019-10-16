# Text_Summarization_with_Tensorflow
Implementation of a seq2seq model for summarization of textual data using the latest version of tensorflow. \
Demonstrated on amazon reviews, github issues and news articles. 

## Prerequisites
- Tensorflow
- nltk
- numpy
- pandas 
- langdetect

## Datasets
I tried the network on three different datasets. 
1. Amazon Fine Food Reviews dataset
2. Github issues dataset
3. All the news dataset

All three of them are available on Kaggle:
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

