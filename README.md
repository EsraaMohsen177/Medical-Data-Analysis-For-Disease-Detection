# Medical Data Analysis for Disease Detection
# overview:
  - This project is a full-stack disease detection system that uses machine learning and NLP to predict possible diseases from user-reported symptoms.
    It features a Flask backend and a responsive Bootstrap frontend.

  ## Frontend
  - Bootstrap 5.3.3   
  - Font Awesome 6.7.2 
  - Chart.js 
  - HTML + CSS + JavaScript
 ## Backend
  - Python 3.9+
  - Flask
  - NLTK 
  - Scikit-learn

# Repository Structure:  
 /src/         → Python Flask backend code
 
 /exe/         → Executables or Jupyter demos 
 
 /static/      → CSS, JS, and icons for frontend
 
 /templates/   → HTML pages
 
 README.md     → This guide

# Requirements: 
 ## Install the following:
  - Python 3.9+
  - pip (comes with Python)
  - Git

 ## Install packages:
  pip install flask nltk scikit-learn

 ## import nltk:
  nltk.download('punkt')
  nltk.download('stopwords')

# Setup Instruction:
 ## option 1 : Run from Source (Recommended)
 
  1- clone the repo:
  
  - git clone 
  https://github.com/YourUsername/YourRepoName.git
  cd Your Repo Name

  2- Create a virtual environment (optional):
  
  - python -m venv env
  env\Scripts\activate      # Windows
  source env/bin/activate   # macOS/Linux

  3- install dependencies:
  
  - pip install -r requirements.txt

  4- Run the server:
  
  - python src/app.py

  5- Open browser at:
  
  - http://127.0.0.1:5000

 ## option 2 : Executable File  

 1. Navigate to /exe/
 2. Download the file (e.g., .exe or .ipynb)
 3. Run directly if .exe OR open with Jupyter if .ipynb

# API Example: 

 ## post / predict
 {
  "symptoms": ["fatigue", "blurred vision"]
 }

 ## Response
 {
  "matched_symptoms": ["Fatigue", "Blurred vision"],
  "predicted_disease": "Diabetes"
 }

# Troubleshooting:

 ModuleNotFoundError: Run pip install flask nltk scikit-learn

 CORS errors: Allow frontend/backend on same origin

 nltk download errors: Ensure internet and Python permissions

# Referances:

 Flask Docs

 NLTK

 Scikit-learn

 Chart.js

 Bootstrap 5



