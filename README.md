# COVID19
This repository contains our experiments for IEEE Access paper. The paper is related to detecting cross cultural emotion and sentiment about COVID-19 pandemic. 
Our experiments start with collection of tweets related to COVID-19 hashtags. We developed LSTM based classifier for emotion and sentiment polarity classification. 
The models used in both the classifiers are available on following links,
Classifier_B model for negative sentiments (https://drive.google.com/file/d/1dbXncfKcSC5fUz5NkSbVmV4CgV2onnCl/view?usp=sharing)
Classifier_C model for positive sentiments (https://drive.google.com/file/d/1dbXncfKcSC5fUz5NkSbVmV4CgV2onnCl/view?usp=sharing)
Classifier_A model for sentiment polarity classification(https://drive.google.com/file/d/1yDSGwOUKsn1zWuFRIHNXi_tueBeaNY04/view?usp=sharing)
Dataset and results are available here (https://drive.google.com/drive/folders/1PiycZZG5vWWXZo8-tHh90_D_2BBno7fE?usp=sharing)
Classfier A is based on LSTM + FastText word embedding.
Classfier B and C are based LSTM + GloVe Twitter word embedding. 
Also, we tested the perfomance of BERT, GRU and BiLSTM to ensure our model selection is correct.
The results of applying BERT on Sentiment140 i.e Classifier A is is available in BERT_Classifier_A.ipynb
Similarlly, BERT on Tweet Emotion Dataset on Positive sentiment polarities  (joy and surprise) is applied in BERT_Classifier_B.ipynb
Finally, BERT on Tweet Emotion Dataset on Negative sentiment polarities  (sad, anger, fear) is applied in BERT_Classifier_C.ipynb
We also test performance of GRU and bi-lstm, the notebooks GRU_Classifier_B and GRU_Classifier_C and bi_lstm_classifier_B, bi_lstm_classfier_C show these experiments and corresponding results
sentiment140_bi_lstm and sentiment140_GRU notebooks present results of applying these models on classfier A in our manuscript. 
