# 🎤 Speech Emotion Recognition using CNN + LSTM

This project classifies emotions from speech audio by extracting Mel-spectrogram features and training a CNN + LSTM hybrid network.

---

## 📌 Dataset

Organize your dataset folder (`data/`) with subfolders for each emotion containing `.wav` files, e.g.:

data/
├─ happy/
│ ├─ audio1.wav
│ ├─ ...
├─ sad/
│ ├─ audio2.wav
│ ├─ ...

yaml
Copy
Edit

---

## ⚙️ Installation

```bash
pip install librosa tensorflow scikit-learn numpy
🚀 Run
bash
Copy
Edit
python speech_emotion_recognition.py

Model
CNN layers extract spatial features from Mel-spectrogram

LSTM captures temporal dynamics

Softmax output for multi-class emotion classification

