#  Fire and Smoke Severity Classification using Deep Learning

##  Project Overview
This project focuses on classifying fire and smoke severity into three categories: Mild, Moderate, and Severe using deep learning techniques. The objective is to build an automated system that can assist emergency response teams in prioritizing and managing fire incidents effectively.

Traditional fire detection systems only identify the presence of fire. This project extends detection to severity classification for smarter decision-making.

---

## Objectives
- Develop a custom fire severity dataset (Mild, Moderate, Severe)
- Implement and compare multiple CNN-based deep learning models
- Apply transfer learning and image augmentation
- Evaluate models using Accuracy, Precision, Recall, and F1-Score
- Identify best-performing model for real-world deployment

---

## Dataset Information
- Custom Fire & Smoke image dataset
- Severity labeling based on:
  - Flame area percentage
  - Brightness analysis
  - K-Means clustering
- Data split:
  - Train: 70%
  - Validation: 20%
  - Test: 10%

---

## Models Implemented

| Model | Validation Accuracy | Test Accuracy |
|-------|--------------------|--------------|
| CNN | 71.8% | 72% |
| ResNet18 | 76.6% | 75.0% |
| ResNet50 | 78.5% | 75.2% |
| EfficientNet-B0 | 76.7% | 77% |

---

##  Best Performing Model
ResNet50 achieved the highest validation accuracy (78.5%) and demonstrated strong generalization capability.

---

##  Methodology
- Image resizing (224×224)
- Normalization and augmentation (flip, rotation, brightness)
- Transfer learning with pretrained CNN architectures
- Adam optimizer with Cross Entropy loss
- Evaluation using confusion matrix and classification report

---

##  Key Observations
- All models showed stable convergence
- Transfer learning significantly improved performance
- EfficientNet-B0 showed balanced performance and efficiency
- Framework can be extended to real-time deployment

---

##  Future Work
- Real-time video-based severity detection
- IoT-based fire alert system integration
- Larger dataset expansion
- Deployment using Flask or Streamlit

---

## Technologies Used
- Python
- PyTorch
- NumPy
- OpenCV
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📁 Project Structure

```
Fire_Detection_DL/
│
├── data/
├── data_preprocessing/
├── models/
├── requirements.txt
└── README.md

##  How to Run

1. Clone repository:
```
git clone https://github.com/Dharshana1103/fire_detection_dl
```

2. Install dependencies:
```
pip install -r requirements1.txt
```

3. Run notebooks in Jupyter

## Author
Dharshana P  
Data Science Student