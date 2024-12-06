# Sentiment Analysis Using BERT

This project implements a sentiment analysis model using the BERT (Bidirectional Encoder Representations from Transformers) architecture. The model is fine-tuned on the Sentiment140 dataset to classify text into positive or negative sentiments.

---

## 📂 Project Structure

- **`data`**: Contains the Sentiment140 dataset used for training.
- **`sentiment_model_hf`**: Directory where the fine-tuned model and tokenizer are saved.
- **`notebook`**: Includes the code for training, testing, and interactive predictions.

---

## 📊 Dataset

The **Sentiment140 dataset** was used for training. It contains tweets labeled as positive (1) or negative (0). The dataset is preprocessed to clean text and remove irrelevant information like URLs, mentions, and special characters.

---

## 🚀 Features

1. **Preprocessing**:
   - Removes URLs, mentions, hashtags, and special characters.
   - Converts text to lowercase.

2. **Model**:
   - Fine-tunes the `bert-base-uncased` model for sentiment classification.
   - Configured for binary sentiment classification.

3. **Training**:
   - Splits the dataset into training and testing sets.
   - Trains the model using TensorFlow with a SparseCategoricalCrossentropy loss function.

4. **Interactive Prediction**:
   - A simple interactive tool to input text and get sentiment predictions with confidence scores.

5. **Saved Model**:
   - The fine-tuned model and tokenizer are saved for future use.

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/KavishaLP/sentiment_analysis.git
   cd sentiment-analysis-bert
