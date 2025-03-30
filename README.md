# 😄 Facial Emotion Recognition (FER) using ResNet18

A deep learning project for recognizing facial emotions using transfer learning with ResNet18, tested on 🧠 benchmark datasets **RAF-DB** and **FER-2013**.

## 🔍 Features
- 🧠 Transfer learning with ResNet18 (ImageNet-pretrained)
- 🧊 Face detection using Haar Cascades (OpenCV)
- 🎨 Data augmentation (cropping, flipping, color jitter)
- 📊 Evaluation using Accuracy, Precision, Recall, F1-Score
- 📈 Visualizations: Training curves, Confusion Matrix, Live Predictions

## 📁 Datasets Used
- 📦 **RAF-DB** – Real-world Affective Faces Database
- 📦 **FER-2013** – Facial Expression Recognition 2013

> 📌 **Classes Used**: Angry, Fear, Happy, Neutral, Sad, Surprise

## ⚙️ Requirements
- Python 3.8+
- PyTorch, torchvision
- OpenCV
- matplotlib
- scikit-learn

## 🚀 Usage
1. Place datasets in `RAF-DB/` and `FER-2013/` directories with `train/` and `test/` folders.
2. Run the notebook or Python script to train models.
3. Use `predict_faces_in_image()` to test emotion prediction on any image. 
