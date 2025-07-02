# ✋ Hand Gesture Recognition using CNN  
A deep learning project for recognizing hand gestures from static grayscale images using Convolutional Neural Networks (CNNs). Built using the LeapGestRecog dataset and trained on pre-recorded gesture images, not real-time input.

---

## 🔍 Overview

This project aims to classify different hand gestures using a deep learning model. It uses a CNN-based architecture trained on the [LeapGestRecog dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog), focusing on static image classification rather than real-time camera input.

---

## 🧠 Model Highlights

- Preprocessing grayscale `.png` images (resized to 64x64)
- CNN model with 2 convolutional layers and dropout for regularization
- Classification into 10 gesture classes (e.g., left swipe, right swipe, etc.)
- Evaluated using classification report and confusion matrix

---

## 🔧 Libraries Used

- `TensorFlow`
- `Keras`
- `OpenCV`
- `NumPy`
- `Matplotlib`
- `Scikit-learn`
- `KaggleHub` (for dataset download)

---

## 🗂️ Dataset

- **Name:** LeapGestRecog
- **Source:** [Kaggle – GTI-UPM](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Structure:** 10 gesture folders inside each user folder (`00`, `01`, ..., `09`)
- Used only the `00` folder in this project for simplicity and class balance

---

## 📁 Project Structure
gesture-recognition/
├── gesture_model.keras # Saved model weights

├── gesture_recognition.ipynb # Main training and evaluation notebook

---
## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gesture-recognition.git
   cd gesture-recognition
   ```
2. Install dependencies
   ```bash
   pip install tensorflow opencv-python numpy matplotlib scikit-learn kagglehub
   ```
3. Run the code:

Use Jupyter Notebook or Python environment 

---

## 📊 Results
Achieved high accuracy with clear validation trends

Accurate prediction of gestures on test samples

Class-wise performance is shown using a confusion matrix and classification report

