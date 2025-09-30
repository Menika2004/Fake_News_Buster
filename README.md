# Fake Buster – Fake News Detection Tool

🔹 Overview

Fake Buster is a machine learning and NLP-based web application designed to detect fake news articles.
It leverages multiple classifiers such as Logistic Regression, Naive Bayes, SVM, Random Forest, and BERT (optional), and provides an interactive Django-based web interface for end users.

🔹 Features

✅ Detects whether a news article is Real or Fake

✅ Supports multiple ML classifiers with performance comparison

✅ Uses NLP preprocessing (tokenization, stop-word removal, TF-IDF, etc.)

✅ Django-based user-friendly web interface

✅ Extendable for real-time news feeds

🔹 Tech Stack

Backend: Python, Django

ML/NLP: Scikit-learn, Pandas, NumPy, NLTK, TF-IDF, (BERT optional)

Frontend: HTML, CSS, Bootstrap

Database: SQLite / MySQL

🔹 Dataset

Dataset used: Fake and Real News Dataset

Size: ~44,000 articles (balanced between real and fake)

🔹 Model Performance (example – update with your results)
Model	Accuracy
Logistic Regression	92%
Naive Bayes	89%
SVM	93%
Random Forest	90%
BERT (optional)	95%
🔹 Installation & Setup
# Clone the repository
git clone https://github.com/your-username/fake-buster.git
cd fake-buster

# Create virtual environment
python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver


Then open http://127.0.0.1:8000/
 in your browser.

🔹 Usage

Paste or upload a news article text into the web interface

Choose the ML model for classification

Get instant Fake / Real results

🔹 Screenshots: 


🔹Input :


<img width="841" height="430" alt="image" src="https://github.com/user-attachments/assets/89518102-4082-4932-99fd-cfd5a0544ebe" />

<img width="841" height="431" alt="image" src="https://github.com/user-attachments/assets/93a3aa02-3fe2-4209-ac37-7aa6232cbaef" />

<img width="841" height="430" alt="image" src="https://github.com/user-attachments/assets/42ed32b9-fb68-44ff-b74e-bc6246aa8a8c" />


🔹Output:


<img width="848" height="432" alt="image" src="https://github.com/user-attachments/assets/a57035c4-51c9-4d96-a508-7acad78031ab" />

<img width="852" height="424" alt="image" src="https://github.com/user-attachments/assets/d40b7dd6-a797-4dca-9e06-f1dc4874e4af" />

<img width="859" height="455" alt="image" src="https://github.com/user-attachments/assets/5753ecb3-eeea-45be-babf-f5c7a0774fbb" />


🔹 Future Enhancements

 Real-time fake news detection via APIs

 Integration with social media feeds

 Deployment on cloud (AWS/Heroku)

🔹 Contributors

👩‍💻 Menika Kumari

🔹 License

This project is licensed under the MIT License – feel free to use and modify.
