# rat-eeg-ai-emotion-classifier
Emotion classification using rat EEG signals
# 🧠 Rat EEG AI Emotion Classifier

A lightweight machine learning pipeline designed to classify emotional states (Calm vs. Aroused) in rats using EEG signals. This project extracts beta and gamma band powers from epicranial EEG and uses a logistic regression classifier to detect shifts in emotional state following whisker stimulation.

> ⚠️ Note: Due to data loss, this repo presents the **architecture, methodology, and concept** of the project. Full code and pre/post stimulus notebooks are partially reconstructed and included as templates.

---

## 📌 Abstract

This work proposes an interpretable method for animal EEG mood classification using frequency band power (beta, gamma) and a logistic regression model. EEG data were segmented into pre- and post-stimulation windows, and frequency-domain features were extracted using Welch's method. A binary classifier achieved **87% accuracy** in distinguishing emotional states, confirming gamma activity as a strong indicator of arousal.


---

## 📊 Dataset

- EEG dataset of 10 rats under left/right whisker stimulation
- 15 channels, sampled at 2 kHz
- Labeled as `Calm` (pre-stimulus) and `Aroused` (post-stimulus)
- Power extracted using Welch’s method

🔗 [Dataset on Figshare](https://figshare.com/articles/dataset/epicranialEEG_10rats_zip/5909122?file=10543897)

---

## 🔍 Methodology Overview

- **Segmentation**: EEG segmented into 256-sample windows with 64-sample overlap
- **Feature Extraction**: Power computed from beta (12–30 Hz) and gamma (30–100 Hz) bands
- **Model**: Logistic regression trained on 70/30 stratified split
- **Accuracy**: 87% with macro-F1 of 0.85

---

## 🧪 Planned Notebooks

- `pre_stimulus_analysis.ipynb`: Code structure for handling Calm segments
- `post_stimulus_analysis.ipynb`: Code structure for Aroused segment processing

---

## 🖥 Planned UI (Future Work)

- Interactive interface for classifying new EEG data (e.g., Streamlit)
- Visualization of power spectra and classification outputs

---

## 📄 Technical Report

A full IEEE-style technical report describing this project is available for review upon request.

> ✉️ Contact: **sk4267@srmist.edu.in** or through GitHub discussions

---

## 🧠 Keywords

`EEG Classification` · `Emotion Detection` · `Beta/Gamma Band` · `Logistic Regression` · `Rat EEG` · `Power Spectral Density` · `Machine Learning` · `Neuroscience`

