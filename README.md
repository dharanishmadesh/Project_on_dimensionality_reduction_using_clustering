# 📡 Human Activity Recognition using Machine Learning

📊 This project implements **Human Activity Recognition (HAR)** using data collected from smartphone sensors and machine learning models.

## 🚀 Features
- 📱 **Dataset**: UCI HAR Dataset (accelerometer & gyroscope data)
- 🎯 **Models**: Naive Bayes classifier
- ⚡ **Feature Selection**: K-Means clustering for dimensionality reduction
- 📈 **Performance Comparison**: Full vs. reduced feature set

## 📥 Installation & Setup
1️⃣ Clone this repository:
```bash
git clone https://github.com/your-username/human-activity-recognition.git
```
2️⃣ Navigate to the project folder:
```bash
cd human-activity-recognition
```
3️⃣ Install dependencies:
```bash
pip install pandas numpy scikit-learn beautifulsoup4 requests
```

## 📊 Dataset
The dataset is automatically downloaded from the **UCI Machine Learning Repository**.
- 📂 **Train/Test Split**: 80-20
- 🔢 **Features**: 561 sensor readings

## ⚙️ Machine Learning Workflow
- 🏗 **Preprocessing**: Standardization, Label Encoding
- 🤖 **Model 1**: Naive Bayes (All Features)
- 🔬 **Model 2**: Naive Bayes (Reduced Features via K-Means)
- 📊 **Metrics**: Accuracy, Training Time

## ▶️ Running the Project
Run the script to train and evaluate the models:
```bash
python har_model.py
```

## 📊 Results
| Model | Features Used | Accuracy | Training Time |
|--------|---------------|-----------|----------------|
| Full Model | 561 | 73.1% | 0.077 sec |
| Reduced Model | 50 | 82.9% | 0.010 sec |

## 🔧 Configuration
Modify `n_clusters` in the script to adjust feature selection:
```python
n_clusters = 50  # Number of clusters for K-Means
```

## 🤝 Contributing
Feel free to **fork the repository** and submit **pull requests** with improvements.

## 📜 License
This project is licensed under the **MIT License**.

---
🌟 **Contributions are welcome!** Feel free to fork, modify, and submit a pull request.

