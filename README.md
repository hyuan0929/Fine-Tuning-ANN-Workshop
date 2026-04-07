# Fine Tuning ANN Workshop

## 📌 Project Overview
This project demonstrates how to use transfer learning with a pre-trained VGG16 model to classify images of cats and dogs.

We implemented:
- Feature extraction (baseline model)
- Fine-tuning (unfreezing top layers)
- Performance comparison
- Data augmentation (bonus)

---

## 🎯 Objectives
- Understand the difference between feature extraction and fine-tuning
- Modify a pre-trained model for a new task
- Evaluate model performance improvements

---

## 👥 Group Information
**Group Name:** Group 1  

**Group Members:**
- Ce Chen (Student ID: 9007166)  
- Haibo Yuan (Student ID: 9010929)  
- Zhuoran Zhang (Student ID: 9048508)

---

## 📊 Methodology

### 1. Data Preparation
- Split dataset into training, validation, and test sets
- Removed corrupted images to avoid training errors

### 2. Feature Extraction (Baseline)
- Used VGG16 with `include_top=False`
- Froze all convolutional layers
- Trained only the classifier

### 3. Fine-Tuning
- Unfroze top convolutional layers
- Used a smaller learning rate
- Improved validation accuracy

### 4. Performance Comparison
- Compared baseline vs fine-tuned model
- Observed slight improvement in validation accuracy
- Detected overfitting from accuracy gap

### 5. Bonus: Data Augmentation
- Applied transformations (rotation, flip, zoom, etc.)
- Reduced overfitting and improved generalization

---

## 📈 Results
- Baseline validation accuracy: ~90%
- Fine-tuned validation accuracy: ~91%
- Data augmentation improved model stability

---

## 🧠 Key Insights
- Transfer learning provides strong baseline performance
- Fine-tuning helps adapt high-level features
- Overfitting is a common issue
- Data augmentation improves generalization

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebook

---

## ⚠️ Notes
- The dataset is not included in this repository (see `.gitignore`)
- Please download the dataset separately before running the notebook

---

## 🔗 GitHub Repository
https://github.com/hyuan0929/Fine-Tuning-ANN-Workshop