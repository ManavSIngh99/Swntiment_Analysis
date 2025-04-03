# Sentiment Analysis using BERT

## Overview

This project implements **Sentiment Analysis** using **BERT (Bidirectional Encoder Representations from Transformers)**. It classifies text into sentiment categories (e.g., Positive, Negative, Neutral) using a pre-trained BERT model from Hugging Face. The model can be fine-tuned on custom datasets for better accuracy in domain-specific tasks.

## Features

- Utilizes a **pre-trained BERT model** for sentiment classification
- Tokenizes text using **Hugging Face Tokenizer**
- Fine-tunes BERT on a dataset for improved accuracy
- Provides **real-time sentiment prediction**
- Supports **custom datasets** for domain-specific applications

## Installation

### Prerequisites

Ensure you have Python 3.7+ installed. Then, install the required dependencies:

```bash
!pip install transformers
```

## Usage

### Steps to Perform Sentiment Analysis:

1. **Load Pre-trained BERT Model** - Utilize a pre-trained BERT model for sentiment classification.
2. **Tokenize Input Text** - Convert text into tokenized format for model processing.
3. **Perform Sentiment Prediction**— Use the model to predict sentiment labels (e.g., Negative, Neutral, and Positive).
4. **Fine-tune on Custom Dataset**—Train the model on a Google Play Store review dataset for better performance in a particular domain.
5. **Evaluate Model Accuracy** - The test accuracy is 73.2%.

## Dataset

- The project can be used with a public dataset like **google-play-store-reviews**.
- The dataset should be preprocessed and tokenized before training or evaluation.

## Model Training

- Fine-tuning BERT on a custom dataset improves sentiment classification accuracy.
- Training involves encoding the text, defining an optimizer, and running multiple epochs for optimization.

## Deployment

- I can deploy this model in the future if needed.

## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests to enhance the project.


### Author: Manav Singh Jadaun

**GitHub:** [ManavSIngh99](https://github.com/ManavSIngh99)


