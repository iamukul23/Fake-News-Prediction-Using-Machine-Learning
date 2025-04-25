📰 Fake News Prediction using Machine Learning
This project is a web application that predicts whether a news article is Fake or Real using machine learning. It uses Python for the backend (with Flask) and HTML/CSS for the frontend. The model is trained using Logistic Regression, TfidfVectorizer, and NLTK for text processing.


🛠️ Tech Stack
Frontend: HTML, CSS

Backend: Python, Flask

ML Libraries: scikit-learn, NLTK, TfidfVectorizer

Model: Logistic Regression

⚙️ How to Run the Project
Clone the repository
git clone https://github.com/your-username/fake-news-prediction.git
cd fake-news-prediction


Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies
pip install -r requirements.txt

Download NLTK data (if needed)
import nltk
nltk.download('punkt')
nltk.download('stopwords')

Run the Flask app
python app.py
