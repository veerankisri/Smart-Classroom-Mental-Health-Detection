# Smart Classroom Mental Health Detection

This project applies a Convolutional Neural Network (CNN) to detect mental health indicators in a classroom setting. It processes facial features from images or video to classify emotional states linked to stress, anxiety, or well-being.  

---

## 📌 Features
- Data preprocessing and augmentation  
- CNN-based model training and testing  
- Accuracy and validation tracking  
- Saved model for reuse or deployment  
- Project report with methodology and findings  

---

## 📂 Files
- `Mental_Health_Detection.ipynb` – training workflow (data preprocessing, CNN model, evaluation)  
- `mental_health_testing.ipynb` – testing workflow for new data  
- `mental_health_expression_model.h5` – trained CNN model  
- `history_accuracy.npy` – training accuracy history  
- `history_val_accuracy.npy` – validation accuracy history  
- `report.pdf` – detailed project report  

---

## ⚙️ Requirements
- Python 3.8+  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

Install dependencies:
```bash
pip install -r requirements.txt
