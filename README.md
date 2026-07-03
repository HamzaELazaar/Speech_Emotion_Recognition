# 🎤 Speech Emotion Recognition using CNN, LSTM and Wav2Vec2

A complete Speech Emotion Recognition (SER) project based on the **RAVDESS** dataset, implementing and comparing three deep learning approaches:

- 🅰️ CNN on Mel-Spectrograms
- 🅱️ LSTM on MFCC features
- 🅲 Fine-tuned Wav2Vec2 Transformer

The notebook includes the entire machine learning pipeline, from dataset preprocessing to model evaluation and deployment through a Gradio interface.

---

## 📌 Project Overview

Speech Emotion Recognition (SER) aims to automatically identify human emotions from speech signals.

This project explores three different architectures:

| Model | Input Features | Framework |
|--------|---------------|-----------|
| CNN | Mel-Spectrograms | TensorFlow/Keras |
| LSTM | MFCC Sequences | TensorFlow/Keras |
| Wav2Vec2 | Raw Audio | Hugging Face Transformers + PyTorch |

The objective is to compare traditional deep learning methods with a modern transformer-based speech model.

---

## 📂 Dataset

This project uses the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** dataset.

The dataset contains recordings from 24 professional actors expressing different emotions.

Supported emotions include:

- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgust
- Surprised

Audio files are sampled at **16 kHz**.

---

## 🚀 Project Pipeline

The notebook is organized into the following stages:

### 1. Environment Setup

- Install dependencies
- Import required libraries
- Configure TensorFlow and PyTorch

### 2. Dataset Preparation

- Upload the RAVDESS dataset
- Extract ZIP archive
- Verify dataset structure
- Create metadata

### 3. Exploratory Data Analysis

- Dataset statistics
- Emotion distribution
- Audio visualization

### 4. Audio Feature Extraction

The notebook extracts several audio representations:

- Mel Spectrograms
- MFCC coefficients
- Raw waveform (for Wav2Vec2)

---

# 🅰️ CNN Model

Pipeline:

- Mel-Spectrogram generation
- Data preprocessing
- CNN architecture
- Training
- Validation
- Confusion Matrix
- Sample prediction
- Model saving

---

# 🅱️ LSTM Model

Pipeline:

- MFCC extraction
- Sequence preparation
- LSTM architecture
- Training
- Evaluation
- Confusion Matrix
- Prediction
- Model saving

---

# 🅲 Wav2Vec2 Fine-Tuning

Pipeline:

- Raw audio loading
- Hugging Face Dataset creation
- Feature extraction
- Fine-tuning
- Evaluation
- Confusion Matrix
- Prediction
- Model saving

---

# 📊 Model Comparison

The notebook compares:

- Classification accuracy
- Training history
- Confusion matrices
- Prediction performance

This allows a direct comparison between classical deep learning methods and transformer-based speech models.

---

# 🎛️ Gradio Interface

An interactive Gradio application is included to:

- Upload a speech sample
- Predict the emotion
- Display the predicted class

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- Librosa
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Gradio

---

## 📁 Repository Structure

```
.
├── SER_RAVDESS_CNN_LSTM_Wav2Vec2.ipynb
├── README.md
└── requirements.txt (optional)
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install tensorflow torch transformers librosa gradio scikit-learn matplotlib pandas numpy
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
SER_RAVDESS_CNN_LSTM_Wav2Vec2.ipynb
```

Upload the RAVDESS dataset when requested and execute the notebook from top to bottom.

---

## 📈 Results

The notebook provides:

- Training curves
- Validation curves
- Accuracy scores
- Classification reports
- Confusion matrices
- Model comparison
- Interactive emotion prediction

---

## 🎯 Learning Objectives

This project demonstrates:

- Audio preprocessing
- Feature engineering for speech
- CNN for spectrogram classification
- LSTM for sequential audio features
- Transfer learning using Wav2Vec2
- Model evaluation
- Speech emotion recognition deployment

---

## 📜 License

This project is intended for educational and research purposes.

---

## 👤 Author

**Hamza Elazaar**

Master's Student in Artificial Intelligence & Digital Computing (AIDC)

Faculty of Sciences and Techniques – Beni Mellal
