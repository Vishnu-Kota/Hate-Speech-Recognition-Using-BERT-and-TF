# Hate-Speech-Recognition-Using-BERT-and-TF
An analysis model that classifies twitter tweets using BERT and Tensor Flow libraries. 

## Libraries used:
- [(Pandas)](https://pypi.org/project/pandas/)
- [(Numpy)](https://pypi.org/project/pandas/)
- [(Shutil)](https://github.com/pfalcon/pycopy-lib)
- [(Tensor Flow)](https://github.com/tensorflow/tensor2tensor)
- [(Sklearn)](https://pypi.org/project/sklearn-pandas/)

## Implementation of text classification with BERT 



This notebook is based in this TensorFlow tutorial: [Classify text with BERT](https://www.tensorflow.org/tutorials/text/classify_text_with_bert)

BERT [(article link)](https://arxiv.org/abs/1810.04805) and other Transformer encoder architectures have been wildly successful on a variety of tasks in NLP (natural language processing). They compute vector-space representations of natural language that are suitable for use in deep learning models.

![](http://www.d2l.ai/_images/nlp-map-pretrain.svg)

Source: http://www.d2l.ai/chapter_natural-language-processing-pretraining/index.html

BERT models are usually pre-trained on a large corpus of text, then fine-tuned for specific tasks.

In this notebook, I am going to use a pretreined BERT to compute vector-space representations of a hate speech dataset to feed two different downsteam Archtectures (CNN and MLP).

Sentiment Analysis

This notebook trains a sentiment analysis model to classify the [Hate Speech and Offensive Language Dataset] tweets in three classes:
 
* 0 - hate speech 
* 1 - offensive language 
* 2 - neither as positive or negative
