# Medical LLM Fine-Tuning Project

## Overview

This project fine-tunes a Large Language Model (LLM) on a medical instruction dataset containing approximately 10,000 medical question-answer pairs collected from multiple sources.

## Dataset

* Dataset: Balanced Medical Instruction Dataset
* Records: 10,000+
* Sources:

  * MedDialog
  * iCliniq
  * ChatDoctor
  * Other medical QA datasets

## Data Processing

* CSV dataset loading
* Data cleaning
* Tokenization
* Label generation for causal language modeling
* Token length analysis
* Dataset visualization

## Exploratory Data Analysis

* Source distribution
* Word frequency analysis
* Word cloud
* PCA visualization
* t-SNE semantic clustering
* Token length distribution

## Model

* Base Model: TinyLlama-1.1B-Chat-v1.0
* Training Method: Supervised Fine-Tuning
* Framework:

  * Transformers
  * Datasets
  * PyTorch

## Training Configuration

* Epochs: 1-3
* Batch Size: 1-2
* Max Sequence Length: 256-512
* Optimizer: AdamW

## Evaluation

* Training Loss
* Validation Loss
* BLEU Score
* ROUGE Score

## Results

The model generates medical question-answer responses based on the fine-tuning dataset.

## Future Work

* LoRA Fine-Tuning
* QLoRA Optimization
* GPU Training
* RAG Integration
* Medical Chatbot Deployment

## Technologies Used

* Python
* Hugging Face Transformers
* PyTorch
* Pandas
* Matplotlib
* Scikit-Learn

