# Human Activity Recognition using LSTM

This project applies a Long Short-Term Memory (LSTM) neural network to recognize human activities from time-series sensor data. It’s a deep learning approach to classify activities like walking, sitting, and standing based on accelerometer and gyroscope signals.

## 📊 Dataset
The dataset contains recordings of 30 participants performing daily activities while wearing a smartphone on the waist.  
Source: [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

## 🧠 Model
We built an LSTM-based neural network using TensorFlow/Keras. The model takes sequential input data and learns to classify the type of human activity.

### Model Architecture:
- Input: Time-series sensor features
- LSTM layers
- Dense layers
- Output: Activity class (6 classes)

## 📈 Results
The model achieved good accuracy on the test set and was able to successfully distinguish between different human activities.

## 📂 Files
- `project neural network.ipynb` — Main notebook with preprocessing, model training, and evaluation

## 🚀 Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy / Pandas / Matplotlib
- Jupyter Notebook

## 📌 How to Run
You can view and run the full notebook on Google Colab:

👉 [Open in Colab](https://colab.research.google.com/github/rowan122/Human-Activity-Recognition-LSTM/blob/main/project%20neural%20network.ipynb)

Just click the link above and it will open the notebook in an interactive environment with all code already executed.
