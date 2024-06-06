# Exploring the impact of the attention mechanism in Arabic text classification

## About
This project investigates how the Attention mechanism improves Arabic text classification. It compares deep learning models, LSTM and CNN, that lack Attention, with AraBert, a Transformer model that utilizes Attention.

## Dataset
Datasets used in the project are found here:
https://sourceforge.net/projects/ar-text-mining/files/Arabic-Corpora/ <br/>
CNN Arabic news dataset: cnn-arabic-utf8 (primary dataset) <br/>
BBC Arabic news dataset: bbc-arabic-utf8

## Models
The following deep learning models were tested:
- **LSTM Model**: A Long short-term memory model for text classification.
- **CNN Model**: A convolutional neural network model for text classification.
- **AraBERT Model**: A transformer-based model specifically designed for Arabic text.

## Notebooks
- `processing-files.ipynb`: Create .csv dataset from the downloaded dataset.
- `preprocessing.ipynb`: Exploratory data analysis (EDA) and preprocessing steps.
- `Data_augmentation.ipynb`: Data augmentation techniques performed.
- `arabic_text_classification_LSTM_CNN.ipynb`: CNN and LSTM models implementation.
- `text_classification_with_AraBert.ipynb`:  AraBERT model implementation.

## Files
- `dataset.csv`: The .csv dataset created from original .txt files.
- `train_data.csv`: Dataset after performing Data Augmentation.
