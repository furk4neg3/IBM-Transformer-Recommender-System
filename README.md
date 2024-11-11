# Pre-Training and Fine-Tuning Transformer Models with PyTorch

This project explores the development of a recommender system for movie reviews using transformer-based neural networks in PyTorch. The project leverages transfer learning by pretraining on a large general-domain text corpus (magazine articles) and fine-tuning on a smaller, domain-specific dataset of movie reviews. By testing different fine-tuning techniques, this project aims to maximize recommendation accuracy while balancing computational efficiency.

## Overview

This project covers:
- **Pretraining** a transformer model for language understanding on a large dataset
- **Fine-tuning** strategies on a smaller, specialized dataset
- Comparison of approaches: full fine-tuning, last-layer tuning, and selective layer unfreezing
- Trade-offs between model generalization and specialization

## Table of Contents

1. [Introduction](#introduction)
2. [Objectives](#objectives)
6. [Requirements](#requirements)
7. [References](#references)

## Introduction

In this project, we build a recommender system for a streaming site based on written movie reviews. Due to the small size of the movie review dataset, we utilize a larger, general-domain text corpus for pretraining to capture broad language patterns. The model is then fine-tuned on the specific dataset of movie reviews, making it better suited for recommendation tasks.

## Objectives

By completing this project, you will:
1. Define and pretrain a transformer-based neural network using PyTorch
2. Fully fine-tune the pretrained model on a different dataset
3. Compare results by fine-tuning only the final layer of the model and selectively unfreezing layers

## Requirements

- Python 3.7+
- PyTorch
- Transformers Library (Hugging Face)

## References

- [IBM AI Engineering Professional Certificate](https://www.coursera.org/professional-certificates/ai-engineer?)
- [Generative AI Engineering with LLMs Specialization](https://www.coursera.org/specializations/generative-ai-engineering-with-llms)
- [Generative AI Engineering and Fine-Tuning Transformers](https://www.coursera.org/learn/generative-ai-engineering-and-fine-tuning-transformers?specialization=generative-ai-engineering-with-llms)
