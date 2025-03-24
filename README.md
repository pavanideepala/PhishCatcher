# PhishCatcher: Client-Side Defence Against Web Spoofing Attacks Using Machine Learning

PhishCatcher is a client-side phishing detection tool designed to protect users from web spoofing attacks. Using machine learning models like Random Forest, SVM, XGBoost, and a Stacking Classifier, PhishCatcher classifies URLs as legitimate or phishing.

## Features
- **Machine Learning Models:** Uses ensemble methods for high accuracy (Stacking Classifier achieves 100%).
- **Client-Side Detection:** No modifications to targeted websites.
- **Flask-Based Web Interface:** Allows users to test URLs.
- **SQLite Integration:** Manages user authentication and URL submissions.
- **Visualization:** Uses Seaborn and Matplotlib for insights.

## Technologies Used
- **Backend:** Flask, SQLite
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Machine Learning:** Scikit-learn, XGBoost
- **Development Tools:** Python, Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PhishCatcher.git
   cd PhishCatcher
   
2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Mac/Linux
   env\Scripts\activate      # On Windows

3. Install dependencies:
   ```bash
   pip install -r requirements.txt


4. Run the application:
   ```bash
  python app.py

