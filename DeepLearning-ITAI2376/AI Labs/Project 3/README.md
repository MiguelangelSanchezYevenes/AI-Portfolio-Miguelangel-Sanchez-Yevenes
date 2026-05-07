
## Problem Statement

The goal of this lab was to compare different deep learning architectures for text and image classification tasks. The project explored how traditional Recurrent Neural Networks (RNNs), LSTM, GRU and ViTs perform on datasets. The challenge was understanding how each architecture processes information differently and determining which models provide the best accuracy/performance.

## Approach and methodology

The lab was divided into multiple sections, Part A, Vanilla RNNs, LSTMs, and GRUs were trained. This showed Text preprocessing which involved sequence conversion and padding. In Part B, DistilBERT was fine-tuned on the same text classification task to compare Transformer performance against RNN-based models and Part C, Vision Transformers (ViTs) were used for image classification on the CIFAR-10 dataset. Hyperparameter tuning experiments were performed throughout the lab.

## Results and evaluation

The results showed clear differences between the architectures. Vanilla RNNs performed the weakest because they struggled with long-term dependencies and suffered from the vanishing gradient problem. LSTM and GRU models improved accuracy and stability due to their gating mechanisms. Gru was also the fastest since it used fewer parameters. DistilBERT achieved the highest performance on text classification because it was already pre-trained on large language datasets.

## Your learning outcomes

I learned:

RNNs, LSTMs, GRUs, and Vision Transformers each have strengths and weaknesses depending on the task.

Experience on using preprocessing data, pre trained models and seeing how they perform.

Pre-training significantly improves performance.
