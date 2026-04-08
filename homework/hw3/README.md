# Homework 3 — Vision-Language Models & Multimodal Fine-Tuning

**Course:** Multimodal AI (MAS.S60 / 6.S985) • Spring 2026 • MIT

## Overview

This assignment focuses on Vision-Language Models (VLMs), including dataset construction, baseline evaluation, and fine-tuning. The goal is to understand how multimodal inputs can be aligned and leveraged within large pretrained models.

## Modalities Explored

| Modality | Description |
|----------|------------|
| Image | Chest X-ray images (ChestMNIST dataset) |
| Text | Question-answer pairs describing medical conditions |
| Multimodal Input | Combined image-text prompts for VLM inference |

## Key Work

- **Dataset construction** — created a multimodal dataset using ChestMNIST with labeled medical images  
- **Data formatting** — structured dataset into image + question + answer format (JSONL)  
- **Baseline inference** — evaluated Qwen2.5-VL model on held-out test samples  
- **Prompt design** — engineered consistent prompts for classification tasks  
- **Multimodal reasoning analysis** — compared model outputs with ground truth labels  
- **Failure mode analysis** — examined hallucinations, ambiguity, and prediction errors  

## Notebook

[`HW3 Notebook`](https://colab.research.google.com/drive/12W2uKO3JgQSnWW8rLqpwO1wJUPsg0C4E?usp=sharing)
