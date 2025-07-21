# EEG Dataset – Rat Emotional State Classification

## 📍 Source
- **Title**: Epicranial EEG Dataset from 10 Rats
- **Link**: [Figshare – epicranialEEG_10rats.zip](https://figshare.com/articles/dataset/epicranialEEG_10rats_zip/5909122?file=10543897)
- **Provided by**: Functional Brain Mapping Laboratory, University of Geneva

## 📈 Description
- EEG recordings from 10 rats during left/right whisker stimulation
- Format: `.eph` files
- 15 EEG channels, sampled at 2 kHz
- Filtered from 1–500 Hz
- Time-locked to stimulation, split into:
  - Pre-stimulus ("Calm")
  - Post-stimulus ("Aroused")

## 📊 Data Size
- 104,640 calm samples
- 209,280 aroused samples
- Segmented into ~4,900 windows of 256 samples with 64 overlap

## 🛠 Processing
- Feature extraction via Welch's method
- Beta (12–30 Hz) and Gamma (30–100 Hz) power bands used
- Data labeled into binary classes: `Calm`, `Aroused`

## 🔒 Licensing
Refer to Figshare terms and conditions for use.

