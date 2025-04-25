# 🫀 Heartbeat Sound Classification

This project focuses on classifying heartbeat sounds into normal or abnormal categories using audio signal processing and machine learning techniques. It was completed as a freelance project and was inspired by the excellent work at [Heartbeat Sound Classifier by smoijueh](https://github.com/smoijueh/Heartbeat-Sound-Classifier).

---

## 📂 Dataset

The dataset used in this project consists of heartbeat audio recordings categorized as:
- **Normal**
- **Abnormal**

These audio files are in `.wav` format and vary in duration and signal quality.

> Dataset Source:Included in description.

---

## 🔧 Preprocessing Steps

- **Resampling** to standardize audio length and frequency.
- **MFCC Feature Extraction** (Mel Frequency Cepstral Coefficients) to represent the audio signals in a way suitable for machine learning models.
- **Label Encoding** for categorical target variable.

---

## 🧠 Model Pipeline

- **Classifier Used:** Convolutional Neural Network (CNN)
- **Training/Test Split:** 70/30
- **Cross-Validation**: Performed using StratifiedKFold
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score

---

## 📊 Results

- ** Highest Accuracy by using Cross-validation:** ~99%
- **Confusion Matrix:** Included in the notebook
- **Feature Importance:** Analyzed using the Random Forest's built-in feature importances

---


