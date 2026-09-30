# Sentiment Analysis Web App

A Flask-based web application that uses Watson NLP API to analyze sentiment in text.

---

## 🚀 Features
- Analyze sentiment of English text (positive, negative, neutral).
- Error handling for invalid or blank inputs.
- Tested with multilingual inputs (French, German, etc.).
- Clean, PEP8-compliant code (10/10 PyLint score).

---

## 📂 Project Structure
practice_project/
├── SentimentAnalysis/
│   └── sentiment_analysis.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── requirements.txt
├── README.md


---

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd practice_project

2.  Create a virtual environment:

bash
python3.11 -m venv env
source env/bin/activate

3. Install dependencies:

bash
pip install -r requirements.txt

4. Run the server:

bash
python server.py

5. Open in browser:

Code
http://127.0.0.1:5000

🧪 Testing
Run unit tests:

bash
python -m unittest test_sentiment_analysis.py
