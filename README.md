Medical Disease Prediction System:
A web application that predicts possible diseases based on symptoms you enter. It also shows recommended precautions, medications, and diets.

How It Works
1.Enter your symptoms in the web page.
2.The system uses a machine learning model to predict possible diseases
3.You get a detailed care plan with description, precautions, medication, and diet advice

What I Used
1.Python with Flask for the website backend
2.Scikit-learn library with SVC model for disease prediction
3.HTML, CSS, JavaScript for the website frontend
4.Pandas for handling the medical data
5.Pickle to save and load the trained model

Key Features
1.Accurate predictions - The model achieved excellent accuracy
2.Easy to use - Simple web interface
3.Complete information - Shows everything from disease description to treatment plans
4.Tested locally - Fully functional on local computer

Files in This Project
1.main.py - Main Flask application
2.model.pkl - Trained machine learning model
3.templates/ - HTML web pages
4.static/ - image
5.data/ - Medical datasets in CSV format


About the Model
1.Uses Support Vector Classifier (SVC) algorithm
2.Trained on medical symptom-disease data
3.All symptoms and diseases were properly encoded for the model
4.Includes data visualization and analysis
