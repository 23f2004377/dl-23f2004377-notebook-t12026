# Music Genre Classification using Deep Learning

**Name:** Arshiya
**Student ID:** 23f2004377

## Project Overview

This project focuses on classifying music genres from audio clips using deep learning techniques. Audio signals are converted into mel-spectrograms and fed into various model architectures including CNNs, CRNNs, and pretrained Audio Spectrogram Transformers (AST).

## Folder Structure

```
dl-23f2004377-notebook-t12026/
├── notebooks/
│   ├── milestone-1.ipynb       # Exploratory data analysis
│   ├── milestone-2.ipynb       # Baseline model
│   ├── milestone-3.ipynb       # CNN from scratch
│   ├── milestone-4.ipynb       # CRNN (CNN + GRU)
│   ├── milestone-5.ipynb       # Fine-tuned AST (transformer)
│   └── final_notebook.ipynb    # Final ensemble submission
├── scripts/                    # Utility and preprocessing scripts
├── data/                       # Dataset directory (not tracked)
└── README.md
```

## Tech Stack

- Python 3.11
- PyTorch
- librosa
- HuggingFace Transformers
- timm
- scikit-learn
- Weights & Biases (wandb)
