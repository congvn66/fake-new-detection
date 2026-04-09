# Fake News Detection with GPT-2

This project explores fine-tuning GPT-2 for fake news detection using text classification.

## Overview
The goal is to adapt a pre-trained GPT-2 model to classify news articles as **real** or **fake**.  
The workflow includes data preprocessing, model fine-tuning, and evaluation.

## Method
- Model: GPT-2 (pre-trained)
- Task: Binary text classification (real vs fake news)
- Approach: Fine-tuning using transfer learning

## Implementation
The entire pipeline is implemented in a single Jupyter/Colab notebook:
- Data loading and preprocessing
- Tokenization
- Fine-tune loop

## Notes
- This is a simple experimental project for exploring language model fine-tuning.
- Designed to run on Google Colab with CPU support.

## Future Work
- Improve performance with larger datasets
- Experiment with other transformer models (e.g., BERT, RoBERTa)
- Add better evaluation and error analysis