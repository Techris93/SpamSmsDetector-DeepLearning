# SpamSmsDetector-DeepLearning
![image](https://i.imgur.com/Iaf6yyR.png)

### Introduction
- In today's world, the internet and social media platforms have become the most efficient and convenient ways of acquiring information. Reviews, opinions, feedback, messages, and recommendations are now considered a significant source of information. -Thanks to technological advancements, we can now extract meaningful information from such data using various Natural Language Processing (NLP) techniques.
- NLP is a branch of Artificial Intelligence (AI) that utilizes computers and human natural language to produce valuable information. NLP is commonly applied in text classification tasks such as spam detection and sentiment analysis, as well as in text generation, language translations, and document classification.

### Objective
- The objective of this article is to explore the utilization of TensorFlow2 for constructing an SMS spam detection model. Specifically, we will develop a binary classification model to determine whether a text message is classified as spam or not (referred to as "Ham").
- Additionally, we will delve into the implementation of Dense, Long Short Term Memory (LSTM), and Bidirectional-LSTM (Bi-LSTM) deep learning models using the TensorFlow2 Keras API.

### Data
- The SMS (text) data was downloaded from [UCI datasets](https://archive.ics.uci.edu/dataset/228/sms+spam+collection). It contains 5,574 SMS phone messages. The data were collected for mobile phone spam research and have already been labeled as either spam or ham.

### Method
Dense text classifier, LSTM, and Bi-LSTM were used and compared in terms of performance.

The following procedures were carried out:
- Load and explore the spam data
![image](https://i.imgur.com/i0uCUV4.png)

- Prepare train test data
![image](https://i.imgur.com/bKRqfjb.png)
![image](https://i.imgur.com/xjPSL3l.png)

- Train the spam detection model using the three approaches mentioned above
![image](https://i.imgur.com/sVEEAC0.png)
![image](https://i.imgur.com/pTCWeNS.png)
![image](https://i.imgur.com/juLioST.png)
![image](https://i.imgur.com/zopNXSA.png)
![image](https://i.imgur.com/DSAHz4I.png)
![image](https://i.imgur.com/zAiVv8S.png)
![image](https://i.imgur.com/ZsDKA20.png)

- Compare and select a final model
- Use the final trained classifier to classify the new messages.
![image](https://i.imgur.com/UYAK2SS.png)

### Conclusion
- In this study, we utilized text messages from UCI datasets to train and evaluate various deep learning models, including Dense architecture, LSTM, and Bi-LSTM. We compared the accuracy and loss of these models on a validation set. Ultimately, we chose the Dense architecture model to classify text messages as either spam or ham, and applied it to classify new incoming messages.



