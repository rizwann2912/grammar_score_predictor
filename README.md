# 🎧 Audio Grammar Scoring Model

A machine learning model that automatically evaluates the grammatical quality of spoken English from audio recordings. This project combines **audio signal processing**, **automatic speech recognition**, and **natural language processing** to extract meaningful features from audio samples and predict grammar scores.

---

## 🧠 Overview

This project implements a comprehensive pipeline to:

1. Process audio files using `librosa`
2. Transcribe speech using **Whisper ASR**
3. Extract linguistic and grammar-based features
4. Train regression models to predict grammar scores
5. Visualize performance metrics and analyze feature importance

---

## 🚀 Features

- 🎵 **Audio Processing**: Extracts acoustic features such as duration, energy, tempo, spectral characteristics, and MFCCs
- 🗣️ **Speech Recognition**: Utilizes OpenAI's Whisper for transcription
- ✍️ **Text Analysis**: Detects grammar errors and evaluates sentence structures
- 📈 **Machine Learning**: Implements XGBoost and Random Forest regressors with cross-validation
- 📊 **Visualization**: Score distribution, feature correlation heatmaps, and importance plots

---

## 📦 Requirements

```bash
pandas
numpy
librosa
torch
transformers
language_tool_python
scikit-learn
xgboost
matplotlib
seaborn
tqdm
