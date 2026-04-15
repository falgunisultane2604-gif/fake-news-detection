📰 Fake News Detection System
📌 Overview

This project is a Machine Learning-based system that detects whether a news article is real or fake using Natural Language Processing (NLP) techniques and classification algorithms. It helps in identifying misinformation and improving content reliability.

📂 Dataset

The project uses the LIAR Dataset, a benchmark dataset for fake news detection.

Dataset Details
Originally contains 6 classes
Converted into binary classification (True / False)
Original Label	Converted Label
True	True
Mostly-true	True
Half-true	True
Barely-true	False
False	False
Pants-fire	False
Final Dataset Columns
Statement → News text
Label → True / False
❓ Why Fake News Detection?
Helps identify misinformation and fake content
Improves media reliability and trust
Useful in social media monitoring
Supports fact-checking systems
⚙️ Key Features
1. Text Classification
Classifies news as True or Fake
2. Multiple ML Models
Logistic Regression
Naive Bayes
SVM
Random Forest
3. Feature Engineering
TF-IDF
Bag-of-Words
N-grams
4. Performance Evaluation
F1-score
Confusion matrix
Learning curves
🧠 Project Workflow
Data Collection → Preprocessing → Feature Extraction →
Model Training → Evaluation → Prediction
🤖 Models Used
Logistic Regression ✅ (Best Performing)
Naive Bayes
Linear SVM
Stochastic Gradient Descent
Random Forest
📈 Performance
Best Model: Logistic Regression
Achieved F1 Score: ~70%

Evaluation Metrics:

Confusion Matrix
Precision-Recall
Learning Curves
🛠️ Technologies Used
Python
Scikit-learn
NumPy
SciPy
NLP Techniques
📁 Project Structure
fake-news-detection/
├── DataPrep.py
├── FeatureSelection.py
├── classifier.py
├── prediction.py
├── train.csv
├── test.csv
├── valid.csv
└── README.md
💾 Installation
Prerequisites
Python 3.6+
pip or Anaconda
Install Dependencies
pip install scikit-learn numpy scipy

OR

conda install scikit-learn
conda install numpy
conda install scipy
▶️ How to Run
Clone the repository
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
Run the prediction script
python prediction.py
Enter news text
Type or paste a news headline
Press Enter
⚡ Example

Input:
"Government launches new education policy"

Output:

Prediction: True
Confidence: 82%
🎯 Applications
Fake news detection systems
Social media monitoring
Fact-checking tools
Content verification platforms
🔮 Future Improvements
Use deep learning models (LSTM, BERT)
Add more dataset features
Improve accuracy with larger datasets
Build web app using Streamlit
Integrate real-time news APIs
🐛 Troubleshooting

Module not found:

pip install -r requirements.txt

Slow prediction:

Reduce dataset size
Use optimized models
