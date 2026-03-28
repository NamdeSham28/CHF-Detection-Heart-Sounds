# CHF-Detection-Heart-Sounds
Detection of Chronic Heart Failure using ML &amp; DL
# Machine Learning and End-to-End Deep Learning for Detection of Chronic Heart Failure from Heart Sounds ❤️‍🩺

## Project Overview

This project presents a hybrid Machine Learning and Deep Learning-based system for detecting **Chronic Heart Failure (CHF)** using phonocardiogram (PCG) heart sound recordings. The system combines **Random Forest** and **Convolutional Neural Networks (CNN)** to classify heart sounds as **Normal** or **Abnormal (CHF detected)** with improved accuracy and reliability.

The proposed model extracts systolic and diastolic features from PCG signals for Machine Learning classification and uses raw audio features for Deep Learning-based prediction. A recording feature aggregation model further improves performance by combining both approaches.

---

## Objectives

* Detect Chronic Heart Failure from heart sound recordings
* Improve classification accuracy using hybrid ML and DL models
* Reduce dependency on manual cardiac auscultation
* Support early-stage diagnosis through automated prediction

---

## Technologies Used

* Python
* Random Forest Classifier
* Convolutional Neural Network (CNN)
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* WFDB Library
* python_speech_features

---

## Dataset

This project uses the **PhysioNet Heart Sound Dataset** containing phonocardiogram (PCG) recordings.

Dataset link:
https://physionet.org/content/challenge-2016/1.0.0/

The dataset includes:

* .dat files → PCG signal data
* .hea files → labels (Normal / Abnormal)
* .wav files → heart sound recordings

Due to GitHub storage limitations, the dataset is not included in this repository.

---

## Project Modules

The system consists of the following modules:

1. Upload PhysioNet Dataset
   Loads heart sound recordings into the application.

2. Dataset Preprocessing
   Extracts systolic and diastolic features and normalizes signals.

3. ML Segmented Model with Feature Extraction & Selection
   Trains Random Forest classifier on extracted features.

4. DL Model on Raw Features
   Applies CNN-based deep learning on raw PCG audio features.

5. Recording Feature Aggregate Model
   Combines ML and DL features for improved prediction accuracy.

6. Predict CHF from Test Sound
   Classifies unseen heart sound recordings as Normal or CHF detected.

---

## Model Workflow

1. Load PhysioNet dataset
2. Extract systolic and diastolic features
3. Train Random Forest classifier
4. Train CNN deep learning model
5. Aggregate features from both models
6. Perform final classification

---

## Performance Summary

* Random Forest Model Accuracy: ~90%
* CNN Deep Learning Model Accuracy: ~93%
* Recording Feature Aggregate Model Accuracy: ~96%

The hybrid approach provides improved prediction performance compared to individual models.

---

## How to Run the Project

Step 1: Install required libraries
pip install -r requirement.txt

Step 2: Run the application
Double-click:
run.bat

OR execute:
python ChronicHeartDetection.py

Step 3:
Upload dataset folder

Step 4:
Run preprocessing and models

Step 5:
Upload test heart sound (.wav file) for prediction

---

## Test Recordings

The repository includes sample test heart sound recordings for prediction testing.

Output:

* Normal
* CHF detected

---

## Folder Structure

CHF-Detection-Heart-Sounds/
│
├── ChronicHeartDetection.py
├── test.py
├── run.bat
├── requirement.txt
├── screens.docx
├── README.md
│
├── testRecordings/
│
└── model/

---

## Applications

* Early detection of Chronic Heart Failure
* Clinical decision support systems
* Remote cardiac monitoring
* AI-based healthcare diagnostics

---

## Future Enhancements

* Integration with LSTM / BiLSTM architectures
* Real-time detection using digital stethoscope devices
* Web-based and mobile deployment
* Multimodal diagnosis using ECG signals

---

## Author

Final Year Engineering Project
Machine Learning and Deep Learning-based CHF Detection System
