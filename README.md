# 🧠 Prostate Cancer Detection Using Deep CNNs

This project uses deep learning techniques to detect **clinically significant prostate cancer** from **Diffusion-Weighted MRI (DWI)** slices. Multiple CNN architectures were trained and evaluated to classify image slices as either **significant (cancerous)** or **not significant (benign)**.

---

## 🚀 Models Used
- ✅ ResNet18  
- ✅ ResNet50  
- ✅ ShuffleNetV2  
- ✅ SqueezeNet

---

## 🗂️ Dataset
- Source: Kaggle – Transverse Plane Prostate MRI Dataset  
- Contains labeled DWI image slices in `train/` and `validation/` folders.

---

## ⚙️ Preprocessing
- Resize to 224x224 pixels  
- Normalization (mean = 0.5, std = 0.5)  
- Grayscale or RGB channel adjustment (for SqueezeNet)

---

## 🧪 Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-Score  
- ROC AUC  
- Confusion Matrix  
- Grad-CAM Visualizations

---

## 📊 Sample Results

| Model        | AUC Score |
|--------------|-----------|
| ResNet50     | 0.89      |
| ResNet18     | 0.86      |
| ShuffleNetV2 | 0.82      |
| SqueezeNet   | 0.78      |

---

## 🛠️ Tech Stack
- Python, PyTorch  
- OpenCV, Matplotlib  
- NumPy, scikit-learn

---

## 📌 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/prostate-cancer-detection-cnn.git
   cd prostate-cancer-detection-cnn
