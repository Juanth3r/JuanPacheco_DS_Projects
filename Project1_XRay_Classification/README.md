# 🏥 Lung X-ray Classification Project

## 📌 Project Overview
This project aims to classify lung X-ray images into four categories:
- **Healthy Lungs**
- **COVID-19**
- **Viral Pneumonia**
- **Bacterial Pneumonia**

We constructed a **custom dataset** by combining two publicly available repositories. The dataset was used to train and evaluate deep learning models for medical image classification.

---

## 🛠️ Technologies & Tools
- **Python** 🐍
- **TensorFlow / Keras** 🧠
- **ResNet50 & Inception-ResNetV2** 🔍
- **Grad-CAM for interpretability** 📊
- **OpenCV & Matplotlib for visualization** 🎨

---

## 🎯 Model Performance
We trained and evaluated two deep learning models:

| Model                  | Test Accuracy |
|------------------------|--------------|
| **ResNet50 (Fine-Tuned)** | **75%**  |
| Inception-ResNetV2 (Baseline) | 69%  |

The **ResNet50 model with optimized hyperparameters** outperformed the baseline model, achieving **75% accuracy on the test set**.

---

## 🔍 Interpretability with Grad-CAM
To understand how the models make predictions, we applied **Grad-CAM (Gradient-weighted Class Activation Mapping)**. This technique highlights the most important regions in X-ray images that influenced the classification decision.

---

## 🚀 How to Use
1️⃣ **Clone the repository:**
```bash
git clone https://github.com/YourUsername/Lung-Xray-Classification.git
```
2️⃣ **Install dependencies:**
```bash
pip install -r requirements.txt
```
3️⃣ **Run the model inference:**
```bash
python classify_xray.py --image sample_image.jpg
```

---

## 📌 Results & Insights
✅ The **ResNet50 model** performed better than Inception-ResNetV2 on this dataset.
✅ The use of **custom dataset creation** improved generalization.
✅ **Grad-CAM** visualizations confirmed that the model focused on relevant lung areas for classification.

---

## 📂 Project Structure
```
📂 Lung-Xray-Classification
│── 📜 README.md
│── 📜 requirements.txt
│── 📂 dataset/
│── 📂 models/
│── 📂 notebooks/
│── 📂 src/
│     ├── preprocess.py
│     ├── train.py
│     ├── evaluate.py
│     ├── classify_xray.py
```

---

## 📩 Contact
👨‍💻 **Juan Alberto Pacheco Paredes**  
📧 [jpachecoparedes@gmail.com] | 🔗 [LinkedIn](https://www.linkedin.com/in/juanpachecods)  
