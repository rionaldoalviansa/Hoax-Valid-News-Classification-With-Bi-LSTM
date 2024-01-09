DESCRIPTION
=================================================================================================================================
<br>This project revolves around the classification of whether news is a hoax or valid based on its content.\n
<br>As an NLP project, this project was done using a deep learning model called Bi-LSTM.\n
<br>With this project, it was hoped that we could help people differentiate between hoaxes and valid news that is currently around.\n


DATASETS
=================================================================================================================================
The dataset contains 600 train data points and 250 test data points.
The classification is performed on this hoax valid news dataset, which contains two classes, valid (373), and hoax (229).


PREPROCESSING
=================================================================================================================================
Multiple preprocessing steps are performed for the dataset cleansing, which includes:
1) Tokenization
2) Lowercasing
3) Punctuation Removal
4) Stopwords Removal (Stemming) by Sastrawi


MODELLING EVALUATION
=================================================================================================================================
Base Bi-LSTM
Accuracy: 91%
f1-score: 91%

Bi-LSTM with TF-IDF + PCA
Accuracy: 64%
f1-score: 49%

Keras Tuner's Randomzied Search-Tuned Bi-LSTM
Accuracy: 93%
f1-score: 93%
