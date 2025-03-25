# Reading-Comprehension-with-BERT-Fine-Tuning

## Overview
This project focuses on solving a reading comprehension task by fine-tuning advanced BERT models. The goal is to answer questions based on contextual passages, leveraging bidirectional contextual embeddings from BERT to achieve high accuracy. The implementation addresses utilizing `bert-base-uncased` and `bert-large-uncased` models with hyperparameter tuning for optimal performance.

## Features
- **Advanced BERT Models**: Utilizes `bert-base-uncased` and `bert-large-uncased` for contextual understanding.
- **Hyperparameter Tuning**: Optimizes learning rate, batch size, and epochs to enhance model accuracy.
- **Efficient Data Processing**: Preprocesses training and test datasets for compatibility with BERT inputs.

## Dataset
The dataset includes:
- **Training Data**: 8,488 samples with context, questions, answer choices, and labels.
- **Test Data**: 2,122 samples.  
Each sample contains:
  - Question ID
  - Context passage
  - Question text
  - Three answer choices (A/B/C)
  - Correct label (training only)

## Requirements
- Python 3.7+
- Libraries: 
  - `transformers` (Hugging Face)
  - `pandas`, `numpy`
  - `torch` or `tensorflow`
- GPU recommended for faster training.

## Usage
1. **Install Dependencies**:
   ```bash
   pip install transformers pandas numpy torch
