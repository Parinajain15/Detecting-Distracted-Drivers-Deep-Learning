# Detecting Distracted Drivers Enhancing Safety using Deep Learning

A deep learning-based computer vision project focused on detecting distracted driving behaviors using ResNet50 architecture and image classification techniques.

---

## Overview

Distracted driving is one of the major causes of road accidents worldwide.  
This project aims to classify different driver activities using deep learning and computer vision methods.

The model predicts various driver behaviors such as:
- Safe driving
- Texting
- Talking on phone
- Drinking
- Reaching behind
- Operating radio
- Talking to passengers

---

## Dataset

State Farm Distracted Driver Detection Dataset

The dataset contains labeled driver images belonging to 10 different activity classes.

### Classes

| Class | Activity |
|------|------|
| c0 | Safe Driving |
| c1 | Texting - Right |
| c2 | Talking on Phone - Right |
| c3 | Texting - Left |
| c4 | Talking on Phone - Left |
| c5 | Operating Radio |
| c6 | Drinking |
| c7 | Reaching Behind |
| c8 | Hair and Makeup |
| c9 | Talking to Passenger |

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV

---

## Model Architecture

This project uses a **ResNet50 (Residual Neural Network)** architecture for image classification.

### Key Features
- Deep CNN architecture
- Residual learning blocks
- Leave-One-Group-Out Cross Validation
- Image preprocessing and normalization
- Bias and variance analysis

---

## Data Preprocessing

The preprocessing pipeline includes:
- Image resizing
- Normalization
- Label encoding
- Dataset shuffling
- Conversion of images into NumPy arrays

---

## Training Configuration

| Parameter | Value |
|------|------|
| Optimizer | Adam |
| Initializer | Glorot Uniform |
| Batch Size | 32 |
| Epochs | 10 |
| Image Size | 64x64 |

---

## Results

| Metric | Score |
|------|------|
| Training Accuracy | 86.95% |
| Validation Accuracy | 40.68% |
| Training Loss | 0.93 |
| Validation Loss | 3.79 |

The project also includes detailed bias-variance analysis and model evaluation.

---

## Project Structure

```bash
Detecting-Distracted-Drivers-Deep-Learning/
│
├── Distracted_Driver_Detection.ipynb
├── README.md
├── requirements.txt
└── supp/
    └── driver.gif
```

---

## Future Improvements

- Real-time webcam integration
- Mobile deployment
- Driver alert system
- Data augmentation
- Hyperparameter tuning
- Higher resolution image training

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Parinajain15/Detecting-Distracted-Drivers-Deep-Learning.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all notebook cells

---

## Author

Developed by :contentReference[oaicite:1]{index=1}
