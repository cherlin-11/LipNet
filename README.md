# Emotion Aware Lip-Reading Using Beam Search Optimized Deep Learning

An advanced deep learning–based lip-reading system that recognizes spoken words from silent video input while simultaneously detecting the speaker’s emotional state. This project extends the LipNet architecture using Beam Search Decoding and Emotion-Aware Recognition for improved contextual accuracy and interaction.

---

# Features

* Lip-reading from silent video input
* Beam search decoding for improved sequence prediction
* Emotion detection alongside speech recognition
* 3D-CNN + Bi-GRU architecture
* CTC loss–based end-to-end learning
* Google Colab compatible
* Supports custom video testing

---

# Technologies Used

* Python 3.12
* TensorFlow / Keras
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib
* Transformers
* Google Colab

---

# Dataset

This project uses the LipNet / GRID Corpus dataset for visual speech recognition.

Dataset is loaded from Google Drive using `gdown`.

---

# Project Architecture

1. Video Input
2. Frame Extraction & Preprocessing
3. 3D-CNN Feature Extraction
4. Bi-GRU Sequence Modeling
5. Beam Search Decoding
6. Emotion Detection Module
7. Final Transcript + Emotion Output

---

# Installation & Setup

## Step 1 — Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/emotion-aware-lipreading.git
cd emotion-aware-lipreading
```

---

## Step 2 — Install Dependencies

```bash
pip install tensorflow keras opencv-python numpy matplotlib scikit-learn transformers gdown
```

---

## Step 3 — Download Dataset

Dataset is automatically downloaded using `gdown`.


## Step 4 — Run the Project

```bash
python main.py
```

OR run directly in Google Colab.

---

# Model Details

## Lip-Reading Model

* 3D Convolutional Neural Networks (3D-CNN)
* Bidirectional GRU (Bi-GRU)
* CTC Loss for alignment-free learning

## Emotion Detection

* Transformer-based emotion classifier
* Detects:

  * Happy
  * Sad
  * Angry
  * Neutral

## Beam Search Decoding

Beam search decoding improves prediction quality by exploring multiple candidate sequences instead of selecting only the locally optimal token.

---

# Results

* Improved contextual consistency compared to greedy decoding
* Better word prediction accuracy
* Simultaneous speech + emotion recognition
* Real-time inference support in Google Colab

---

# Applications

* Assistive technology for hearing-impaired individuals
* Silent speech interfaces
* Human-computer interaction
* Surveillance systems
* Emotion-aware AI assistants

---

# Future Improvements

* Real-time webcam deployment
* Mobile application integration
* Multilingual lip-reading support
* Larger emotion-labeled datasets
* Transformer-based sequence modeling

---

# Author

Cherlin Flory Thomas
B.Tech Artificial Intelligence and Data Science



This project is developed for academic and research purposes.
