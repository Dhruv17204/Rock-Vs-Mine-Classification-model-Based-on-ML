# 🪨 Rock vs Mine Classification Using Machine Learning

## 🔍 Overview
This project is based on classifying sonar signals as either **rock** or **mine** using supervised machine learning algorithms. It demonstrates how sonar data can be used to build a predictive model that distinguishes between undersea rocks and metal objects (like mines).

## 🧠 Problem Statement
Sonar signals reflected off objects underwater can help identify whether the object is a rock or a mine. The goal of this project is to classify these objects accurately using machine learning techniques.

## 📁 Dataset
- **Dataset**: [UCI Machine Learning Repository – Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs+rocks)
- **Features**: 60 numeric attributes per sample representing energy in different frequency bands
- **Target**: `M` for Mine, `R` for Rock

## ⚙️ Tech Stack
- Python 3.8+
- Pandas, NumPy – Data processing
- Scikit-learn – Model building and evaluation
- Matplotlib, Seaborn – Visualization
- Jupyter Notebook – IDE

## 🔄 Workflow
1. Data loading and exploration
2. Preprocessing and label encoding
3. Train-test split
4. Model training using Logistic Regression
5. Evaluation using accuracy score
6. Visualization of predictions

## 📊 Results
- **Model Used**: Logistic Regression
- **Accuracy**: ~83%
- Evaluation metrics include confusion matrix and classification report.

## 🧪 How to Run
```bash
# Clone the repo
git clone https://github.com/Dhruv17204/Rock-Vs-Mine-Classification-model-Based-on-ML.git
cd Rock-Vs-Mine-Classification-model-Based-on-ML

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook "Rock vs Mine Prediction.ipynb"
```

## 💡 Future Improvements
- Try other models (SVM, Random Forest, XGBoost)
- Hyperparameter tuning
- Model deployment via Streamlit

## 👨‍💻 Author
**Dhruv Manoj Patil**  
📧 dhruvpatil1724@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/dhruv-patil) | [GitHub](https://github.com/Dhruv17204)
