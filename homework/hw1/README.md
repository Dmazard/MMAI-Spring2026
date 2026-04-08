# Homework 1 — Multimodal Healthcare Data Preprocessing

**Course:** Multimodal AI (MAS.S60 / 6.S985) • Spring 2026 • MIT

## Overview

This assignment is focused on the design and preparation of a multimodal healthcare data set in order to complete a downstream machine learning task(s). The aim of this effort was to identify a clinically relevant problem statement and the construction of a data set comprised of several modalities (e.g. Time-Series signals, clinical text and derived features).


## Modalities Explored

| Modality | Description |
|----------|------------|
| Time-Series Data | Vital signs and physiological signals over time |
| Clinical Text | Transcribed patient information and notes |
| Audio Features | Extracted MFCC and log-mel spectrogram representations |
| Structured Labels | Emotion or classification labels from dataset |

## Key Work

- **Dataset design & objective** — defined a multimodal prediction task for early clinical deterioration using healthcare-inspired data  
- **Data acquisition & preprocessing** — used the SUPERB dataset and processed raw audio into structured formats  
- **Feature extraction pipeline** — generated MFCCs, log-mel spectrograms, and transcripts using Whisper  
- **Multimodal alignment strategy** — organized modalities into synchronized representations for model input  
- **Data visualization** — applied t-SNE to visualize feature distributions and modality separability  
- **Metadata construction** — built a structured dataset linking audio, features, transcripts, and labels  

## Notebook

[`HW1 Notebook`](https://colab.research.google.com/drive/1FeEVZU-y_RekMb3a99MU7MHp3GHcAz7k?usp=sharing)
