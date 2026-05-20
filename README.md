# AI-Driven Diabetic Retinopathy Detection using Deep Learning

## 📌 Project Overview

This project focuses on detecting and classifying Diabetic Retinopathy (DR) using Deep Learning and Convolutional Neural Networks (CNN). Diabetic Retinopathy is a diabetes-related eye disease that can lead to blindness if not detected early.

The system classifies retinal fundus images into five categories:

- Mild
- Moderate
- No_DR
- Proliferate_DR
- Severe

The project was developed as part of the SuPrazo Technologies Internship Assessment for the Jr. AI/ML Intern role.

---

## 🎯 Objectives

- Build an AI-powered image classification system
- Detect diabetic retinopathy stages from retinal images
- Train a CNN model using TensorFlow/Keras
- Evaluate model performance using validation accuracy and loss metrics

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn
- Google Colab

---

## 📂 Dataset Information

The dataset contains retinal fundus images categorized into five classes:

| Class | Description |
|------|-------------|
| Mild | Early stage diabetic retinopathy |
| Moderate | Moderate retinal damage |
| No_DR | No diabetic retinopathy |
| Proliferate_DR | Advanced stage with abnormal blood vessel growth |
| Severe | Severe retinal damage |

### Dataset Distribution

| Class | Images |
|------|--------|
| Mild | 370 |
| Moderate | 999 |
| No_DR | 1805 |
| Proliferate_DR | 295 |
| Severe | 193 |

Total Images: **3662**

---

## ⚙️ Project Workflow

1. Dataset Loading
2. Data Preprocessing
3. Image Rescaling & Augmentation
4. Train-Validation Split
5. CNN Model Building
6. Model Training
7. Performance Evaluation
8. Prediction & Visualization

---

## 🏗️ Model Architecture

The project uses a Simple CNN (Convolutional Neural Network) architecture consisting of:

- Convolutional Layers
- Max Pooling Layers
- Dropout Layers
- Dense Fully Connected Layers
- Softmax Output Layer

---

## 📈 Model Performance

### Training Details

- Training Samples: 2931
- Validation Samples: 731
- Epochs: 15
- Optimizer: Adam
- Learning Rate: 0.0001

### Final Results

✅ Validation Accuracy: **68.13%**

The model showed steady improvement during training and successfully learned retinal image patterns for DR classification.

---

## 📊 Visual Results

Project screenshots and outputs are available inside the `screenshots/` and `results/` folders.

Included:
- Dataset Distribution
- Training Accuracy Graph
- Loss Graph
- Prediction Outputs
- Training Logs

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/AI-Driven-Diabetic-Retinopathy-Detection.git
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open Notebook

Run the notebook using:

- Google Colab
OR
- Jupyter Notebook

---

## 📁 Repository Structure

```text
AI-Driven-Diabetic-Retinopathy-Detection/
│
├── DR_Classification_Notebook.ipynb
├── README.md
├── requirements.txt
├── screenshots/
├── results/
├── model/
└── dataset_info/
```

---

## 💡 Challenges Faced

- Handling imbalanced dataset classes
- Long CNN training time
- GPU configuration in Google Colab
- Image preprocessing and resizing

---

## 🤖 AI Tools Used

The following tools were used during development:

- ChatGPT → debugging, explanations, documentation support
- Google Colab Documentation
- TensorFlow Documentation

---

## 📚 Learnings

Through this project, I learned:

- CNN model development
- Medical image classification workflow
- Data preprocessing techniques
- GPU-based model training
- Model evaluation and visualization
- Deep learning project organization

---

## 🔮 Future Improvements

- Use Transfer Learning models like EfficientNet or ResNet
- Improve dataset balancing
- Deploy as a web application
- Increase prediction accuracy
- Add real-time prediction interface

---

## ⭐ Conclusion

This project demonstrates the practical application of Deep Learning in the healthcare domain for automated diabetic retinopathy detection. The system successfully classifies retinal images into multiple DR severity levels and highlights the potential of AI-assisted medical diagnosis.
