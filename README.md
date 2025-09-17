# Hate Speech Classification Model

## Overview
This repository contains a transformer-based model fine-tuned on the StanfordNLP IMDB dataset for hate speech detection in text. It classifies input sentences into two categories: "Hate Speech" or "Not Hate Speech" using the `xlm-roberta-base` pretrained model.

## Model Details
- **Base Model:** `xlm-roberta-base`
- **Dataset:** StanfordNLP IMDB dataset (5,000 random samples)
- **Metrics:** Accuracy (~86.3%), Macro F1-score (~86.3%)
- **Libraries:** Transformers, Torch, Evaluate

## Features
- Tokenization and attention masking with XLM-RoBERTa tokenizer
- Fine-tuned binary classification for hate speech detection
- Evaluation using accuracy and macro F1-score metrics

## Installation

1. Clone the repository
