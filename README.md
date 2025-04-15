# Behavioral-Biometrics-in-Forensics

## 🔍 Overview
This project proposes a novel AI-based framework that enhances forensic investigations by utilizing **behavioral biometrics**, with a primary focus on **facial micro-expression recognition**. Traditional forensic methods often face limitations when physical evidence is insufficient, tampered, or deliberately obfuscated. This research explores how **deep learning techniques** can help uncover subtle behavioral cues that are difficult to fake, enabling more accurate and reliable identification in forensic scenarios.

![Model Flow](Research%20Model%20Flow%20Diagram2.jpg)

## 🧠 Core Components
- **Input**: CASME II Micro-Expression Dataset
- **Preprocessing**: Grayscale conversion, frame resizing (128x128), sequence generation
- **Model Architecture**: CNN layers for spatial feature extraction combined with LSTM layers for temporal sequence learning
- **Evaluation**: Standard classification metrics including accuracy, precision, recall, and F1-score across emotion categories

## ⚙️ Technologies Used
- Python (PyTorch)
- OpenCV, NumPy, Matplotlib
- Scikit-learn
- Deep Learning (CNN + LSTM Hybrid Architecture)

## 🧬 Forensic Significance
This approach aims to:
- Improve identification in scenarios where physical evidence is incomplete or unavailable
- Leverage subtle behavioral signals like micro-expressions for suspect profiling
- Provide robust, AI-driven tools that complement traditional forensic methods
- Enable explainable and ethical integration of AI into judicial processes

## 📌 Future Directions
- Extend to other behavioral modalities such as gait analysis and keystroke dynamics
- Improve model generalization using diverse, real-world datasets
- Integrate attention mechanisms and transformer-based architectures
- Collaborate on legal, ethical, and judicial guidelines for behavioral AI

---

> ⚠️ **Note:** This is an ongoing research project. Results are under review and not yet published. Please cite accordingly and reach out for collaboration or academic use.

