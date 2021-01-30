# Emotion Classifier

This project classifies a sentence into 14 emotion categories and also devised a novel way to detect a sentence which doesn't fall into any of the category:
1.  angry
2.  ashamed
3.  afraid
4.    sentimental
5.    hopeful
6.    apprehensive
7.    sad
8.    happy
9.    faithful
10.    confident
11.    caring
12.    grateful
13.    impressed
14.    jealous
15.    surprised

The dataset used for training is based on Facebook AI research paper [Towards Empathetic Open-domain Conversation Models](https://arxiv.org/pdf/1811.00207.pdf)

The model was trained by fine-tuning facebook's BART pretrained model.

Model Performance:
|Macro F1 score| Average accuracy|
|--------------|-----------------|
| 0.77         | 0.79            |
