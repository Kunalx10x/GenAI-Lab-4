# GenAI-Lab-4
# CSET419: Text Generation with RNN/LSTM and Transformers

## Objective
[cite_start]The objective of this lab is to design and implement simple text generation models that can learn patterns from a given text corpus and generate new sequences[cite: 4].

## Dataset
[cite_start]The models were trained on a specialized corpus covering Artificial Intelligence, Machine Learning, and Transformer architectures [cite: 29-71].

## Architectures Implemented

### Component I: RNN / LSTM
- [cite_start]**Architecture**: Embedding Layer -> LSTM (150 units) -> Dense (Softmax)[cite: 25].
- **Key Metric**: Achieved a training accuracy of **99.17%** and a loss of **0.1418**.
- [cite_start]**Technicality**: Uses a hidden state to manage temporal dependencies through gating mechanisms (Input, Forget, Output)[cite: 17, 44].

### Component II: Transformer
- [cite_start]**Architecture**: Multi-Head Self-Attention -> Positional Encoding -> Feed-Forward Network[cite: 78, 79].
- **Key Metric**: Achieved a final loss of **0.0949**.
- [cite_start]**Technicality**: Leverages parallel processing and self-attention to capture global context across the corpus.

## Results
Both models successfully generated coherent text based on the training data. [cite_start]The Transformer model showed faster convergence and a lower final loss compared to the LSTM[cite: 45, 50].
