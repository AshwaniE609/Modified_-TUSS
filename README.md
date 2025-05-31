# TUSS: Audio Source Separation

This repository contains code and resources for **TUSS**, a deep learning-based audio source separation project. The goal is to separate individual sources (such as different speakers or instruments) from a mixed audio recording.

---

## Features

- PyTorch-based neural network for audio separation
- Custom dataset loader for mixtures and sources
- Training and evaluation scripts
- Spectrogram visualization tools

---

## Directory Structure

├── tuss/
│ ├── models/
│ │ ├── tuss.py
│ │ └── config.py
│ ├── dataset.py
│ └── train.py
├── audio1/
│ ├── Tr1.WAV
│ ├── output0.wav
│ ├── output1.wav
│ ├── output2.wav
│ └── output3.wav
├── plot_spectrogram.py
├── README.md
└── requirements.txt
