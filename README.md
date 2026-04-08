
📰 Fake News Detection System

An intelligent Machine Learning project that detects whether a news article is real or fake using Natural Language Processing (NLP) and classification algorithms.

✨ Features
🔍 Text Classification – Classifies news as True or Fake
🧠 Multiple ML Models – Logistic Regression, Naive Bayes, SVM, Random Forest
📊 Feature Engineering – TF-IDF, Bag-of-Words, N-grams
⚡ Fast Predictions – Input news headline and get instant results
📈 Performance Evaluation – F1-score, confusion matrix, learning curves
🛠️ Tech Stack
Technology	Purpose
Python	Core programming
Scikit-learn	Machine learning models
NumPy	Numerical computations
SciPy	Scientific computing
NLP Techniques	Text preprocessing
📊 Dataset

This project uses the LIAR Dataset, a benchmark dataset for fake news detection.

Dataset Details
Originally contains 6 classes
Reduced to binary classification:
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
⚙️ Project Workflow
📥 Data Collection
🧹 Data Preprocessing (Tokenization, Stemming)
🔎 Feature Extraction (TF-IDF, N-grams)
🤖 Model Training
📊 Model Evaluation
🚀 Prediction
📁 Project Structure
fake-news-detection/
├── DataPrep.py          # Data preprocessing
├── FeatureSelection.py  # Feature extraction
├── classifier.py        # Model training & evaluation
├── prediction.py        # Final prediction script
├── train.csv
├── test.csv
├── valid.csv
└── README.md
🚀 Installation
Prerequisites
Python 3.6+
pip or Anaconda
Install Dependencies
pip install scikit-learn numpy scipy

OR (Anaconda)

conda install scikit-learn
conda install numpy
conda install scipy
▶️ How to Run
Step 1: Clone Repository
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
Step 2: Run Prediction Script
python prediction.py
Step 3: Enter News Text
Type or paste a news headline
Press Enter
Output
✅ Prediction: True / Fake
📊 Probability Score
🤖 Models Used
Logistic Regression ✅ (Best Performing)
Naive Bayes
Linear SVM
Stochastic Gradient Descent
Random Forest
📈 Performance
Best model: Logistic Regression
Achieved F1 Score ~70%
Evaluated using:
Confusion Matrix
Precision-Recall
Learning Curves
⚡ Example
Input:
"Government launches new education policy"

Output:
Prediction: True
Confidence: 82%
🔮 Future Improvements
 Use deep learning (LSTM, BERT)
 Add more dataset features
 Improve accuracy with larger data
 Build web app (Streamlit)
 Real-time news API integration
🐛 Troubleshooting
Issue: Module not found
pip install -r requirements.txt
Issue: Slow prediction
Reduce dataset size
Use optimized models
💡 Tips
Use clean and meaningful text input
Avoid very short sentences
More context = better prediction
🤝 Contributing
Fork repository
Create new branch
Make changes
Submit Pull Request
📜 License

This project is open-source and available under the MIT License.
