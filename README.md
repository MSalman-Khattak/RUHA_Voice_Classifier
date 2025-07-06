# RUHA Voice Command Classifier Web App

This project is built using the RUHA dataset and demonstrates the training of five machine learning classifiers on voice command data. It also includes a Flask-based web application to interactively test model predictions and display performance analytics.

## 🔍 Features

- Preprocesses audio dataset using `librosa`, `pydub`, and `soundfile`.
- Trains 5 different classifiers using `scikit-learn`.
- Displays evaluation metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
- Flask web interface to input voice/text commands and view classifier predictions.
- Interactive performance analytics page for classifier comparison.


## 🛠️ Installation

# 1. Clone this repo:
   ```bash
   git clone https://github.com/...........


## Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # on Windows use venv\Scripts\activate

## Install dependencies:
pip install -r requirements.txt

