# Bidirectional LSTM for Emotion Classification

The aim of this project is to implement a Bidirectional LSTM based model to detect emotions from text. The Pipeline for this implementation is given below.

![image](https://user-images.githubusercontent.com/61133251/163887539-bea10cc0-3dc2-4c9f-b269-0688e0688786.png)

This project was implemented on top of a pre-existing Kaggle notebook. Added to this notebook is: <br> 
> Text preprocessing using TextHammer
> Word Embeddings using Gensim API

The final model architecture is provided below.
![image](https://user-images.githubusercontent.com/61133251/163887917-b8ce3907-d16a-4b71-8af7-2c2a38440bbc.png)

This model was able to provide impressive results even with a low number of epochs. The precision and recall for 'Suprise' class is also quite satisfactory.
<img width="581" alt="image" src="https://user-images.githubusercontent.com/61133251/163887883-8b06e2c4-0f87-4d4e-b09c-8e91df79d3b9.png">


References:
1. Dataset - https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp
2. Reference Implementation - https://www.kaggle.com/code/deepakvedantam/emotion-classification-using-bidirectional-lstm/data
