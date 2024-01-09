DESCRIPTION
=================================================================================================================================
This project revolves around the classification of whether news is a hoax or valid based on its content.
<br>As an NLP project, this project was done using a deep learning model called Bi-LSTM.
<br>With this project, it was hoped that we could help people differentiate between hoaxes and valid news that is currently around.


DATASETS
=================================================================================================================================
The dataset contains 600 train data points and 250 test data points.
<br>The classification is performed on this hoax valid news dataset, which contains two classes, valid (373), and hoax (229).


PREPROCESSING
=================================================================================================================================
Multiple preprocessing steps are performed for the dataset cleansing, which includes:
1) Tokenization
2) Lowercasing
3) Punctuation Removal
4) Stopwords Removal (Stemming) by Sastrawi


MODELLING EVALUATION
=================================================================================================================================
Base Bi-LSTM Evaluation
<br>Accuracy: 91%
<br>f1-score: 91%

<br>Bi-LSTM with TF-IDF + PCA Evaluation
<br>Accuracy: 64%
<br>f1-score: 49%

<br>Keras Tuner's Randomzied Search-Tuned Bi-LSTM Evaluation
<br>Accuracy: 93%
<br>f1-score: 93%
