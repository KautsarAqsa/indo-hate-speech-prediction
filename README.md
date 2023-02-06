# Indonesian Language Hate-Speech Prediction
This repository contains a supervised machine learning model for predicting hate speech in Indonesian language. Models that have been trained and evaluated 
are logistic regression, lightGBM, and neural-network models. 
The dataset used was Indonesian tweet dataset from: 
https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection

There are 4 notebooks in this repo. Ideal order for reading:
`Hatespeech_Cleaning.ipynb` -> `Hatespeech_Logistic_Regression.ipynb` -> `Hatespeech_LightGBM.ipynb` -> `Hatespeech_NN.ipynb`

## Prerequisites
You will need to have the following software installed (already installed on Google Colab):

- Python 3
- Jupyter Notebook
- Scikit-learn
- LightGBM
- TensorFlow
- Pandas
- Numpy

Notebook | Description | Colab
------------- | ------------- | -------------
`Hatespeech_Cleaning.ipynb` | Starting notebook of this project, in NLP, how we cleanse the data is the most crucial part.| [![open-in-colab]](https://colab.research.google.com/drive/1Mn0TFFP0nwD31hcfPa6_Q1VC6pQhg0SJ?usp=sharing)
`Hatespeech_Logistic_Regression.ipynb` | Start predicting hate-speech with classical model | [![open-in-colab]](https://colab.research.google.com/drive/1IHP1ZK2zdXqxoqkU1tjow1SeSiHXfcGP?usp=sharing)
`Hatespeech_LightGBM.ipynb` | Trying hate-speech prediction with boosting model (best performance!) | [![open-in-colab]](https://colab.research.google.com/drive/1G-g2jN4ZaRYQM9xIOQj1nRqfxUiv0mkX?usp=sharing)
`Hatespeech_NN.ipynb` | Trying hate-speech prediction with deep learning model | [![open-in-colab]](https://colab.research.google.com/drive/1lHJcip92ybxK5UE6UfKTxFWLsEDDFiwF?usp=sharing)

This repository provides a starting point for using supervised machine learning to predict hate speech in Indonesian language. The models provided are intended as a baseline, and further development is required to improve their performance.

[open-in-colab]: https://colab.research.google.com/assets/colab-badge.svg
