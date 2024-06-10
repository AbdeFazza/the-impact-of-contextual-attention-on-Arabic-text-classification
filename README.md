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
- `preprocessing.ipynb`: Exploratory data analysis (EDA) and preprocessing steps, performed on the primary dataset CNN.
- `Data_augmentation.ipynb`: Data augmentation techniques performed.
- `arabic_text_classification_LSTM_CNN.ipynb`: CNN and LSTM models implementation for Arabic text classification.
- `text_classification_with_AraBert.ipynb`:  AraBERT model implementation for Arabic text classification.
- `arabic-sentiment-analysis-lstm-cnn (1).ipynb`: Arabic tweets sentiment analysis using LSTM and CNN.
- `AraBERT_text_classification_and_sentiment_analysis.ipynb`: AraBERT model implementation for Arabic text classification + Arabic tweets sentiment analysis.

## Files
- `dataset.csv`: The .csv dataset created from original .txt files.
- `bbc-arabic-utf8_folder_form.rar`: Primary dataset: BBC Arabic news in a folder structure. Each folder corresponds to a specific category and contains .txt files related to that category.
- `cnn-arabic-utf8_csv_form.zip`: CNN dataset in .csv format.
- `train_data.csv`: Dataset after performing Data Augmentation.
