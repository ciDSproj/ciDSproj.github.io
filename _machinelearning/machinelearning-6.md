---
title: "IMDB Sentiment Classification with LSTM"
excerpt: "Built a neural network model that classifies movie reviews from the IMDB dataset as positive or negative using an LSTM architecture. This project demonstrates deep learning model development, evaluation, and custom text inference.<br/>"

collection: machinelearning
---
In this project I built a binary sentiment classifier using the IMDB movie reviews dataset. The model uses an **Embedding layer**, an **LSTM layer with dropout**, and **Dense layers** to learn patterns in text sequences. After preprocessing and padding sequences to a fixed length, the model achieved **86% test accuracy** on unseen test data.
<br/>

[GitHub](https://github.com/ciDSproj/imdb_reviews)

---


The training curves show a good learning pattern:  
- **Accuracy:**Both training and validation accuracy curves improve steadily and stay close to each other, indicating good generalization.  
- **Loss:** The gap between the training and validation loss curves remains small, suggesting the model is not overfitting.  

Overall, the model learns effectively across the three epochs, achieving strong performance on both training and validation sets.



<img src='/images/ml6_training_history.png'>



To make the model interactive, I added a custom prediction function that encodes and pads any user‑provided review text, 
allowing the network to generate sentiment predictions with associated probabilities. 
