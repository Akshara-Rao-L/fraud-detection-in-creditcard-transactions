fraud-detection-in-creditcard-transactions
Project Overview
A machine learning-based web application for detecting fraudulent financial transactions in real-time. This system analyzes transaction data using a pre-trained Random Forest model to identify suspicious patterns and potential fraud with high accuracy.

Key Features
Real-time Prediction: Instant fraud analysis of transaction data
Confidence Scoring: Probability-based results with interpretable metrics
Security Focus: Designed to protect against financial fraud
AI-Powered: Utilizes advanced machine learning techniques
Responsive Design: Works seamlessly across devices

Tech Stack
Backend:
Python Flask
Scikit-learn
Joblib (model persistence)
NumPy

Frontend:
HTML5/CSS3 (with modern CSS variables)
JavaScript (ES6)
Font Awesome Icons
Google Fonts

Machine Learning:
Random Forest Classifier (primary model)
Autoencoders (anomaly detection)
GANs for synthetic fraud sample generation*

* Mentioned in project description

Performance Metrics
Model	Accuracy	Precision	Recall	F1-Score
Random Forest	0.89	0.90	0.89	0.89
Autoencoders	0.50	0.49	0.50	0.38

Installation & Usage
Clone repository:

bash
git clone https://github.com/yourusername/fraud-detection-system.git
cd fraud-detection-system
Install dependencies:

bash
pip install flask scikit-learn joblib numpy
Run the application:

bash
python app.py
Access the web interface at: http://localhost:5000

Input Parameters
The system analyzes 19 transaction features including:
Transaction amount and type
Account balance
Device information
Historical fraud patterns
Temporal features (time, day, weekend)
Authentication methods
Geographical indicators

Project Structure
fraud-detection-system/
├── app.py                 # Flask application
├── static/
│   └── style.css          # Custom styles
├── templates/
│   └── index.html         # Main interface
├── requirements.txt       # Dependencies
└── random_forest_fraud_model.pkl  # Trained model

Future Enhancements
Integration with payment gateways
Real-time transaction monitoring
Adaptive learning system
Enhanced visualization dashboard
Multi-model ensemble approach

Contributors
Akshara Rao

License
MIT License
