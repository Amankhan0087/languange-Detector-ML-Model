🎯 Language Detection Model

Identify the language of any text using Machine Learning, NLP, and Google Translate API

<p align="center"> <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/NLP-Project-green?style=for-the-badge" /> <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge" /> <img src="https://img.shields.io/badge/API-Google%20Translate-red?style=for-the-badge" /> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" /> </p>

🚀 Project Overview

This project predicts the language of any given text using:

NLP preprocessing

TF-IDF vectorization

Multinomial Naive Bayes classifier

Google Translate API (dataset generation)

It’s lightweight, accurate, and ideal for beginners exploring NLP + ML.

🧰 Tech Stack
Tool / Tech	Purpose
Python 3.10	Programming language
Scikit-Learn	Machine Learning model
Pandas / NumPy	Data handling
Google Translate API	Dataset creation
Matplotlib / Seaborn	Visualizations
🚀 How It Works

📥 Collect dataset using Google Translate API

🧹 Clean + preprocess text

🔤 Convert text using TF-IDF Vectorization

🧠 Train model using Multinomial Naive Bayes

🧪 Save & test predictions

🧪 Example Prediction
input_text = "Bonjour, comment allez-vous ?"
model.predict([input_text])

Output:
['French']

📂 Project Structure
project-folder/
│── data/
│── notebooks/
│── model/
│── src/
│   ├── preprocess.py
│   ├── train.py
│   └── predict.py
│── README.md
│── requirements.txt

📥 Installation
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
pip install -r requirements.txt

🏃 Run the Project
python src/train.py
python src/predict.py

📊 Training Results

(Add accuracy graphs or confusion matrix screenshots here)

🤝 Contributing

Pull requests are welcome!

⭐ Support

If you like this project, give it a ⭐ — it helps a lot!
