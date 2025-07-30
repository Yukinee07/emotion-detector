# Facial Emotion Recognition and Face Detection 👁️🗨️😊

**Intelligent Systems Semester Project: Real-Time Face Detection & Emotion Classification using Deep Learning**

_Kulliyyah of Information and Communication Technology, IIUM_  
_Group: Artificial Stupidity_

## 🚀 Project Overview

This project implements an end-to-end facial emotion recognition system using Deep Learning and Computer Vision. By leveraging a custom-trained Convolutional Neural Network (CNN) for emotion classification and integrating the MTCNN algorithm for robust face detection, the system can:
- **Detect multiple human faces** in real-world images or live webcam feeds.
- **Classify facial emotions** into seven categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.
- Generate instant insights from images or live video, making it valuable for customer feedback analysis and Human-Computer Interaction (HCI) scenarios.

This repository includes:
- All source code for data preprocessing, model training, deployment, and experiment scripts.
- The **final group project report** (`PDF`) with in-depth methodology, results, and discussion.
- Links to our demo and reproducible Google Colab notebook.

## 📄 Report & Resources

- **[Full Project Report (PDF)](PATH/TO/IS-Final-Group-Project-1.pdf)**  
  *(Upload the file and update the link if needed; replace `PATH/TO/...` accordingly)*

## 🌏 Explore Online

- 📒 **Google Colab (Full Code, Ready to Run):**  
  [colab.research.google.com/drive/1OvA5j66II0X3FVnja7aiAQ8j5Y6vj3uo?usp=sharing](https://colab.research.google.com/drive/1OvA5j66II0X3FVnja7aiAQ8j5Y6vj3uo?usp=sharing)

- ▶️ **Live System Demo (YouTube):**  
  [youtu.be/oHWkWC97bl0](https://youtu.be/oHWkWC97bl0)

## 🧠 Dataset

- **FER2013**: 48x48 pixel grayscale face images, 7 emotions, ~36K labeled samples  
- Preprocessing, training/validation/test splits, and augmentation strategies are fully documented in the code and report.

## 🏗️ How To Use

### 1. **Run Online on Google Colab (No Installation Needed)**
- Open the provided [Colab Notebook](https://colab.research.google.com/drive/1OvA5j66II0X3FVnja7aiAQ8j5Y6vj3uo?usp=sharing).
- Upload the FER2013 dataset and run through each section to train the model, test results, and try live photo uploads.
- The notebook covers data preparation, model training, evaluation, inference on new images, and code for real-time deployment.

### 2. **Run Locally (Advanced)**
- Clone this repository:
  ```
  git clone https://github.com/yourusername/face-emotion-cnn.git
  cd face-emotion-cnn
  ```
- [Optional] Set up a virtual environment and install dependencies:
  ```
  pip install -r requirements.txt
  ```
- Run the Python scripts for:
    - **Training**: `python train_emotion_model.py`
    - **Testing on images**: `python test_on_images.py`
    - **Live webcam emotion detection**: `python webcam_emotion_detection.py`
- Adjust file paths in the scripts as needed for your data and model checkpoints.

### 3. **View the PDF Report**
- The full `IS-Final-Group-Project-1.pdf` report provides methodology, architecture details, results analysis, and references.

## ✨ Features

- **Robust Face Detection:** Multi-task Cascaded CNNs (MTCNN) for varied lighting, angles, and backgrounds.
- **Emotion Recognition:** Custom CNN architecture for accurate 7-class emotion prediction.
- **Live & Batch Inference:** Works with both static images and real-time camera streams.
- **Detailed Results Visualization:** Confusion matrices, classification reports, and step-by-step result plots.
- **Colab & Local Support:** Use it in the cloud, or locally for advanced/research purposes.

## 💡 Team

- Muhammad Amirul Haziq Bin Muhamad Hasmahadi
- Muhammad Umair Asyraaf Bin Samsuri
- Yusuf Mohammad Yunus
- Suhaib Adnaan
- Alnatsheh Huthifa M J

_Supervised by Dr. Amir ‘Aatieff Bin Amir Hussin_

## 🔖 References

- FER2013 Dataset ([Kaggle Link](https://www.kaggle.com/datasets/msambare/fer2013))
- See full bibliography in the attached project report

**Let us know your feedback or issues via GitHub!**
*The code, architecture, and methodology are freely released for academic exploration and further research.*
