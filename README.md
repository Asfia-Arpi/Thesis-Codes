# An Energy-Efficient Deep Learning Model for Breast Cancer Detection

A deep learning-based framework for **breast cancer detection from histopathological images**, focusing on accurate classification, model robustness, computational efficiency, and adaptability across different image magnification levels.

> **Thesis Project — B.Sc. in Software Engineering**  
> **Department of Software Engineering, Daffodil International University**

---

## 👩‍💻 Author

**Asfia Haque Arpi**  
B.Sc. in Software Engineering  
Daffodil International University

**Thesis Supervisor:**  
Mr. Suprove Chandra Sarkar  
Lecturer, Department of Software Engineering  
Daffodil International University

---

## 📌 Overview

Breast cancer is one of the major health challenges affecting women worldwide. Accurate and reliable diagnosis from histopathological images can support early detection and clinical decision-making.

This thesis investigates deep learning-based approaches for **binary breast cancer classification (Benign vs. Malignant)** using histopathological images.

The study evaluates multiple pretrained CNN architectures and explores hybrid/ensemble approaches to improve classification performance while considering computational efficiency.

---

## 🎯 Research Objectives

The main objectives of this research are:

- Improve the generalization capability of deep learning models.
- Explore energy-efficient deep learning model design.
- Develop a robust model for breast cancer detection from histopathological images.
- Improve adaptability across different histopathological image magnification levels.
- Investigate hybrid/ensemble deep learning approaches for improved classification performance.

---

## 🔬 Research Scope

This research focuses on:

- Histopathological breast cancer images.
- Binary classification:
  - **Benign**
  - **Malignant**
- Deep learning-based image classification.
- Multiple magnification levels.
- Fine-tuned pretrained CNN architectures.
- Hybrid/ensemble deep learning models.
- Computational efficiency and training cost considerations.

The study does not focus on mammogram-based datasets or multiclass breast cancer classification.

---

## 🗂️ Dataset

The experiments were conducted using the **Breast Cancer Histopathological Database (BreakHis)**.

The dataset contains histopathological images categorized into benign and malignant classes and includes multiple magnification levels:

- 40×
- 100×
- 200×
- 400×

### Classes

| Class | Description |
|---|---|
| Benign | Non-cancerous tissue |
| Malignant | Cancerous tissue |

> **Note:** The original dataset should be obtained from its official source. The dataset itself is not included in this repository due to size and licensing considerations.

---

## 🧠 Models Evaluated

Several pretrained CNN architectures were investigated during the study:

- EfficientNetB0
- EfficientNetB2
- MobileNetV2
- MobileNetV3Small
- ResNet50
- InceptionV3
- VGG16
- VGG19

The study first evaluates individual pretrained CNN models and then investigates hybrid/ensemble combinations.

---

## ⚙️ Methodology

The overall workflow consists of the following stages:

```text
Histopathological Images
          ↓
Data Preprocessing
          ↓
Data Augmentation
          ↓
Train / Validation / Test Split
          ↓
Pretrained CNN Models
          ↓
Fine-Tuning
          ↓
Performance Evaluation
          ↓
Hybrid / Ensemble Models
          ↓
Final Performance Analysis
```

### Main stages

1. Dataset preparation
2. Image preprocessing
3. Data augmentation
4. Dataset splitting
5. Transfer learning
6. CNN fine-tuning
7. Model evaluation
8. Hybrid/ensemble experimentation
9. Comparative performance analysis

---

## 📊 Experimental Results

The research compared individual fine-tuned CNN architectures and hybrid models using classification performance metrics.

### Fine-Tuned CNN Models

The experiments included:

- EfficientNetB0
- EfficientNetB2
- MobileNetV2
- ResNet50

Performance was evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Loss
- Confusion Matrix
- Training time

---

## 🔗 Hybrid / Ensemble Models

Hybrid experiments included combinations such as:

- EfficientNetB0 + MobileNetV2
- EfficientNetB0 + ResNet50

The purpose of the hybrid approach was to investigate whether combining complementary deep feature representations could improve classification performance.

---

## 🏆 Key Result

The proposed experimental framework achieved a maximum reported classification accuracy of approximately:

### **95.95% Accuracy**

The results indicate that the investigated fine-tuned and hybrid deep learning approaches can achieve strong performance for binary breast cancer classification from histopathological images.

> Results should be interpreted as experimental findings on the selected dataset and should not be considered a substitute for clinical diagnosis.

---

## 📈 Evaluation

The repository includes code for generating and/or analyzing:

- Training vs. validation accuracy curves
- ROC-AUC curves
- Confusion matrices
- Classification metrics
- Model comparison results

Example evaluation workflow:

```text
Model Prediction
      ↓
Confusion Matrix
      ↓
Precision / Recall / F1
      ↓
ROC-AUC
      ↓
Model Comparison
```

---

## 📁 Repository Structure

```text
breast-cancer-deep-learning/
│
├── README.md
│
├── notebooks/
│   ├── model-1.ipynb
│   ├── model-2.ipynb
│   ├── model-3.ipynb
│   └── hybrid_models.ipynb
│
│
├── results/
│   ├── figures/
│   ├── confusion_matrices/
│   ├── roc_curves/
│   └── model_comparison/
│
├── presentation/
│   └── Final_Defense_Presentation.pdf
│
├── requirements.txt
│
└── LICENSE
```

> Update the folder names above according to the actual files in this repository.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV
- Jupyter Notebook
- Google Colab / GPU environment

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone [YOUR_GITHUB_REPOSITORY_URL]
cd [YOUR_REPOSITORY_NAME]
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare the dataset

Download the BreakHis dataset from the appropriate official/source repository and organize the dataset according to the paths expected by the notebooks/scripts.

### 4. Run preprocessing

Open:

```text
notebooks/data_preprocessing.ipynb
```

and execute the preprocessing and dataset preparation steps.

### 5. Train the models

Run the model training notebooks/scripts:

```text
notebooks/model_training.ipynb
```

### 6. Evaluate the models

Run:

```text
notebooks/model_evaluation.ipynb
```

to generate evaluation metrics, ROC curves, and confusion matrices.

### 7. Run hybrid experiments

For hybrid/ensemble experiments, use:

```text
notebooks/hybrid_models.ipynb
```

---

## 📚 Research Contribution

The research primarily investigates:

1. Comparative evaluation of multiple pretrained CNN architectures.
2. Fine-tuning of deep learning models for histopathological breast cancer classification.
3. Exploration of hybrid/ensemble architectures.
4. Evaluation across different histopathological magnification levels.
5. Consideration of computational cost and energy efficiency during model development.

---

## 🔮 Future Work

Potential future improvements include:

- Evaluation on larger multi-hospital datasets.
- External validation using independent datasets.
- Integration of clinical or genomic information.
- Development of a user-friendly clinical application.
- Further optimization for resource-constrained environments.
- Investigation of explainable AI techniques for clinical interpretability.

---

## 📄 Thesis & Presentation

### Thesis

https://drive.google.com/file/d/1B35gz83tXIAuMjfMJNmM_qyvDJh9bD3V/view?usp=sharing

### Final Defense Presentation

https://docs.google.com/presentation/d/1GS0jPBhR1NznjVpfZykeFU-wA0_ARhID/edit?usp=sharing&ouid=118365993967817975088&rtpof=true&sd=true

---

## ⚠️ Disclaimer

This project is developed for **academic and research purposes**.

The models presented in this repository are not intended to replace professional medical diagnosis or clinical decision-making.

---

## 📬 Contact

**Asfia Haque Arpi**

- GitHub: https://github.com/Asfia-Arpi
- LinkedIn: www.linkedin.com/in/asfiahaque-arpi
- Email: arpiasfi7@gmail.com

---

## ⭐ Acknowledgment

Special thanks to my thesis supervisor **Mr. Suprove Chandra Sarkar**, Lecturer, Department of Software Engineering, Daffodil International University, for his guidance and support throughout this research.
