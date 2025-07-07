# 🏃‍♂️ Human Activity Recognition Using LSTM Networks

## 📌 Overview

This project focuses on **classifying human physical activities** using sensor data from smartphones and smartwatches. By using a **Long Short-Term Memory (LSTM)** neural network, the model learns temporal patterns in the time-series data to accurately recognize activities such as **walking, running, sitting, standing, climbing stairs,** and **lying down**.

This task is crucial in fields like **healthcare monitoring, fitness tracking, and wearable computing**.

## 🎯 Objectives

- Preprocess accelerometer and gyroscope data
- Design and train an LSTM-based deep learning model
- Evaluate using metrics: **accuracy**, **precision**, **recall**, and **F1-score**
- Address class imbalance and improve model generalization

## 📁 Dataset

You can use either of the following datasets:

### 1. UCI HAR Dataset  
- 📌 Activities: Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Lying  
- 📱 Sensors: Accelerometer and Gyroscope at 50Hz  
- 👥 30 participants  
- 🔗 [Download Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

### 2. WISDM Dataset (Used in this project)  
- 📌 Activities: Walking, Jogging, Sitting, Standing, Climbing Stairs  
- 📱 Sensors: Accelerometer at 20Hz  
- 👥 36 participants  
- 🔗 [Download Dataset](https://www.cis.fordham.edu/wisdm/dataset.php)

## 🧠 Model Architecture

- Input: Time-series windows of accelerometer data
- Network: **LSTM layers** + Dense layers
- Output: Softmax layer for multi-class classification
- Framework: TensorFlow / Keras

## 🔬 Research Basis

**Paper**: _"Deep Learning for Sensor-based Activity Recognition: A Survey"_  
**Authors**: Jianfei Yang et al.  
📚 Discusses the use of RNNs, CNNs, and hybrid models for HAR tasks, along with data preprocessing, feature learning, and evaluation strategies.  
🔗 [arXiv Link](https://arxiv.org/abs/1801.07119)

## 📊 Results

- Achieved strong classification accuracy across multiple activities
- Used stratified evaluation to assess model performance
- Generated confusion matrix and per-class metrics
- Explored potential for generalization to unseen users

## 🧪 Notebook Features

✅ Complete preprocessing pipeline  
✅ LSTM model training and evaluation  
✅ Visualizations (loss, accuracy, confusion matrix)  
✅ Techniques to handle imbalanced classes  
✅ Model ready to test on new sequences

## 🛠️ Tools & Libraries

- Python, NumPy, Pandas, Matplotlib
- TensorFlow / Keras
- Scikit-learn
- Jupyter Notebook

## 🏷️ GitHub Tags

`human-activity-recognition`, `LSTM`, `deep-learning`, `time-series`, `tensorflow`, `wearable-computing`, `sensor-data`, `HAR`, `RNN`
