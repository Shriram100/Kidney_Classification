# Kidney_Classification
A Flask-based Machine Learning web application that predicts whether a patient is likely to have a Chronic Kidney Disease from 24 clinical features.
The app loads a pre-trained scikit-learn model from best_chronic_kidney_diseasemodel.pkl and exposes a REST API endpoint (POST /predict) that accepts JSON input and returns a clear prediction message.
Includes a basic home route (/) for the UI and a small test.py script to validate predictions locally.
