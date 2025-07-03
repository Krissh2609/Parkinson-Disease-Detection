# Parkinson’s Disease Detection using Machine Learning

This project builds a machine learning model to detect Parkinson’s Disease based on voice features like jitter, shimmer, HNR, etc.

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Features: Voice frequency, jitter, shimmer, NHR, RPDE, etc.
- Target: `status` (1 = Parkinson’s, 0 = Healthy)

## ⚙️ Model
- Algorithm: Random Forest Classifier
- Accuracy: **93%**
- High recall (98%) for Parkinson’s cases

## Tools and Libraries used
- Python
- Jupyter Notebook
- Used various tools like Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn

## 📁 Files
- `parkinsons_model.ipynb`: Main notebook with data processing, training, and evaluation
- `requirements.txt`: Python libraries used

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook parkinsons_model.ipynb

