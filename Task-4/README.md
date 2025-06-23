📧 Email Spam Detection using Machine Learning
🔍 Overview
Email spam is a common cyber threat where unsolicited messages flood users’ inboxes. In this project, we developed a machine learning model that classifies emails as spam or not spam based on their content. The system processes raw text, extracts meaningful features, and applies classification algorithms to effectively detect unwanted emails.

This task was completed as a part of an internship program at Oasis Infobyte.

📂 Project Structure
bash
Copy
Edit
📁 Email-Spam-Detection
├── 📄 spam_detection.ipynb        
├── 📄 spam.csv                    
├── 📄 README.md                   
├── 📁 models/                    
└── 📁 images/                     
📊 Dataset
The dataset contains labelled email messages:

label: Indicates whether the message is spam or ham (not spam)

text: The actual email content

Sample:

label	text
ham	"Hey, are we still on?"
spam	"Win a FREE ticket now!"

Dataset Source: UCI ML Repository - SMS Spam Collection Dataset

🛠️ Technologies Used
Python

Pandas, NumPy

NLTK (Natural Language Toolkit)

Scikit-learn (SVM, Naive Bayes, etc.)

TF-IDF Vectorizer

Matplotlib & Seaborn for visualization

📌 Key Steps
Data Loading & Preprocessing

Removed unwanted characters, stopwords, punctuation

Tokenization, stemming using NLTK

Feature Extraction

Transformed text into numeric vectors using TF-IDF

Model Building

Trained various models: Multinomial Naive Bayes, Support Vector Machine (SVM)

Chose the best performing model using accuracy, precision, recall

Evaluation

Confusion matrix

Accuracy, Precision, Recall, F1-Score

📈 Results
Model	Accuracy
Naive Bayes	97.5%
Support Vector Classifier	98.3%

The SVM model provided the best results.
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook spam_detection.ipynb
🎓 What I Learned
Text preprocessing techniques in NLP

Feature extraction using TF-IDF

Spam detection using supervised learning

Model evaluation metrics and their interpretation

🙏 Acknowledgements
Special thanks to Oasis Infobyte for the opportunity and support.

Dataset: UCI ML Repository – SMS Spam Collection

Author : Purnapriya tammana










