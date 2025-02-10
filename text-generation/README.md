# Text Generation with LSTM using Wikipedia data

This project focuses on text generation using a Long Short-Term Memory (LSTM) model trained on the WikiText-2 dataset. The dataset consists of featured articles from Wikipedia. The goal of this project is to generate coherent and contextually relevant text based on the learned patterns from the dataset.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
<!--- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)-->

## Overview
This project implements a text generation model using an LSTM neural network. The model is trained on the WikiText-2 dataset, which contains over 2 million tokens from Wikipedia articles. After training, the model can generate text based on a given seed input.

Key features include:
- Preprocessing pipeline to tokenize and prepare the WikiText-2 dataset.
- LSTM-based architecture for capturing sequential and contextual dependencies in text.
- Text generation functionality to produce new text based on learned patterns.

## Dataset
The WikiText-2 dataset is a collection of high-quality Wikipedia articles, curated for language modeling tasks. It includes:
- **Training set**: 2,088,628 tokens
- **Validation set**: 217,646 tokens
- **Test set**: 245,569 tokens

<!--The dataset is preprocessed to handle tokenization, vocabulary creation, and sequence batching for training.-->

## Model Architecture
The text generation model is based on an LSTM (Long Short-Term Memory) network. The architecture is as follows:
- **Embedding Layer**: Converts token indices into dense vectors.
- **LSTM Layer**: Captures sequential dependencies in the text.
- **Fully Connected Layer**: Maps LSTM outputs to vocabulary-sized logits.
- **Softmax Layer**: Converts logits into probabilities for text generation.
