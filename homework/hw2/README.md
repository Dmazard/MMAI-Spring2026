# Homework 2 — Multimodal Fusion & Alignment (AV-MNIST)

**Course:** Multimodal AI (MAS.S60 / 6.S985) • Spring 2026 • MIT

## Overview

This assignment explores multimodal learning through unimodal baselines and fusion techniques using the AV-MNIST dataset. The focus is on understanding how alignment and fusion strategies impact performance across modalities.

## Modalities Explored

| Modality | Description |
|----------|------------|
| Image | Handwritten digit images |
| Audio | Spectrogram representations of spoken digits |
| Multimodal Fusion | Combined representations of image and audio features |

## Key Work

- **Unimodal modeling** — implemented and trained separate image and audio models for classification  
- **Performance comparison** — evaluated modality effectiveness (image significantly outperforming audio)  
- **Hyperparameter tuning** — experimented with learning rates and model configurations  
- **Fusion implementation** — built a late-fusion architecture using concatenation and MLP head  
- **Alignment insights** — analyzed how representation quality impacts fusion performance  
- **Evaluation metrics** — measured accuracy and loss across unimodal and multimodal setups  

## Notebook

[`HW2 Notebook`](https://colab.research.google.com/drive/1XLgVA7LQOwcBnUZ7Vw3HxpI2H-VUpWax?usp=sharing)
