# 📦 Image-Based Entity Value Extraction

## 🎯 Project Overview
This project focuses on extracting entity values 📊 (such as **weight, volume, dimensions**) from product images using **Machine Learning** techniques. The approach involves:

- 🧠 **Optical Character Recognition (OCR)** for textual information
- 🖼️ **Convolutional Neural Networks (CNN)** for visual features

Both techniques work together to improve entity extraction accuracy. 🚀

---

## ⚙️ Setup and Installation
Follow these steps to set up the project:

1. 📥 **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. 📦 **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. 📊 **Download and preprocess the dataset:**
   ```bash
   python data_preparation.py
   ```

---

## 🚀 Usage

Perform the following steps to use the model:

- 🛠️ **Prepare the data:**
   ```bash
   python data_preparation.py
   ```
- 📈 **Extract features:**
   ```bash
   python feature_extraction.py
   ```
- 🎯 **Train the model:**
   ```bash
   python model_training.py
   ```
- 📊 **Generate predictions:**
   ```bash
   python predict.py
   ```

---

## 🧩 Model Architecture
The hybrid architecture consists of:

- 🧠 **OCR Branch:** Embedding layer ➡️ LSTM
- 🖼️ **CNN Branch:** Pre-extracted features processed by fully connected layers
- 🔗 **Combined Output:** Concatenated features passed through fully connected layers

---

## 📊 Performance Metrics
- ✅ **Validation Accuracy:** **87%**
- 📈 **F1 Score:** **0.85**

---

## 📈 Future Improvements
- 🎭 Implement **data augmentation** techniques
- 🔍 Explore **advanced OCR methods**
- 🛠️ Fine-tune hyperparameters using **Bayesian Optimization**

---

## 📞 Contact
For any questions or issues, please feel free to:
- 🐙 Open an **issue** in the GitHub repository
- 📧 Reach out via email

Thank you for checking out the project! 🎉
