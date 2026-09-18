# Deep Learning for Generalization and Sentiment Analysis

This repository contains my solution for the second Deep Learning assignment at the Technion – Israel Institute of Technology.

The project combines theoretical analysis and practical implementation of modern deep learning techniques. It explores model generalization, overfitting, recurrent neural networks for Natural Language Processing (NLP), and Transformer fundamentals.

---

## Project Overview

The assignment is divided into three main parts:

- Generalization and overfitting experiments
- Sentiment analysis using recurrent neural networks
- Theoretical analysis of CNNs and Transformers

---

# Part 1 – Generalization and Overfitting

The first part investigates one of the fundamental concepts of deep learning: the difference between memorization and generalization.

A fully connected neural network is trained on the MNIST dataset using completely random binary labels.

The experiment demonstrates that modern neural networks possess enough capacity to perfectly memorize meaningless labels while completely failing to generalize to unseen data.

### Topics explored

- Overfitting
- Memorization
- Generalization
- Model capacity
- Dataset size vs model complexity
- Cross-Entropy loss
- Adam optimization
- Training vs testing behavior

The project also includes a discussion of practical methods for reducing overfitting at the:

- Data level
- Model level
- Training level

An academic paper on overfitting reduction is reviewed and summarized.

---

# Part 2 – Sentiment Analysis with Recurrent Neural Networks

The second part focuses on binary sentiment classification using the IMDB movie review dataset.

A complete NLP pipeline is implemented from raw text to final predictions.

## Data Processing Pipeline

The project includes:

- Raw text loading
- Text cleaning
- Word-level tokenization
- Vocabulary construction
- Unknown token handling
- Padding
- Start/End of sentence tokens
- Sequence truncation
- Word embeddings using `nn.Embedding`

A custom dataset class is implemented for efficient loading and preprocessing.

---

## Models

Two recurrent architectures are implemented and compared.

### Vanilla RNN

A multi-layer recurrent neural network is trained for sentiment classification.

### LSTM

A multi-layer Long Short-Term Memory network is implemented using:

- Learned word embeddings
- Multiple recurrent layers
- Dropout regularization
- Fully connected classification head

The performance of both architectures is compared throughout training.

---

## Model Evaluation

Several evaluation techniques are included:

- Training accuracy
- Test accuracy
- Training loss
- Test loss
- Accuracy curves
- Loss curves
- Confusion matrices

The project also discusses:

- Training stability
- Optimization behavior
- Generalization performance
- Hyperparameter selection
- Architectural decisions

---

# Part 3 – Deep Learning Theory

The final section covers theoretical questions on modern deep learning architectures.

Topics include:

### Convolutional Neural Networks

- Interpretation of convolution kernels
- Image filtering effects

### Transformers

- Self-attention complexity
- Computational efficiency
- Key-Value caching
- Transformer Encoder vs Decoder
- Appropriate architecture selection for NLP tasks

---

## Technologies

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib
- Google Colab

---

## Repository Contents

- Complete notebook implementation
- Assignment specification
- Training code
- Evaluation results
- Model visualizations

---

## Topics Covered

- Deep Learning
- Neural Networks
- Generalization
- Overfitting
- Memorization
- Natural Language Processing (NLP)
- Sentiment Analysis
- Word Embeddings
- Recurrent Neural Networks (RNN)
- LSTM
- Sequence Modeling
- Text Classification
- Cross-Entropy Loss
- Adam Optimizer
- Regularization
- Confusion Matrix
- CNN Theory
- Transformers
- Self-Attention

---

## Key Takeaways

This project combines both theoretical understanding and practical implementation of deep learning techniques. It demonstrates how neural networks behave under severe overfitting conditions, develops complete NLP pipelines for sentiment analysis, compares recurrent architectures, and explores the theoretical foundations of convolutional and Transformer-based models.
