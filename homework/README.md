# Homework 3 — Vision-Language Models & Multimodal Fine-Tuning

**Course:** Multimodal AI (MAS.S60 / 6.S985) • Spring 2026 • MIT

## Overview

This assignment is focused on Vision Language Models (called VLMs); dataset construction, baseline evaluation, and fine-tuning. This assignment will allow students to understand how to use multimodal inputs in conjunction with large pre-trained models through the alignment/leveraging of versions of these datasets during the entire modelling process. 

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
