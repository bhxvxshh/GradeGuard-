# GradeGuard-
is a web app that predicts student performance using machine learning (SVM). Users input grades and personal information, and the app predicts if they are a "Top Student" or "Low Student." Results are sent via email, offering valuable insights for both students and educators.
# GradeGuard: AI-Powered Student Performance Prediction

**GradeGuard** is a web-based application that predicts student performance based on their grades in subjects like English, Math, Science, and Language. The system uses a trained Support Vector Machine (SVM) model to determine if a student is a "Top Student" or a "Low Student" and sends the prediction to the student's email address.

## Features:
- Input grades for multiple subjects (English, Math, Science, Language).
- Submit additional student data like nationality, city, gender, and ethnic group.
- Predict student performance (Top/Low) using a trained machine learning model.
- Receive the prediction results via email.
- View average grades and the latest performance in a user-friendly report.

## Installation:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/bhxvshh/GradeGuard.git
   cd GradeGuard
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set up your environment variables for Flask-Mail and model:

Replace the email configuration (MAIL_USERNAME, MAIL_PASSWORD) with your own credentials in the Flask app configuration.
Make sure to place your trained model file (best_svm_model.pkl) in the project folder.
Run the Flask app:

bash
Copy code
python app.py
Open the application in your browser:

Navigate to http://127.0.0.1:5000/ to use the web application.
Tech Stack:
Backend: Flask (Python Web Framework)
Machine Learning: Scikit-Learn, Support Vector Machine (SVM)
Email Service: Flask-Mail (SMTP for sending emails)
Data Processing: Pandas (for data manipulation), NumPy
Frontend: HTML, CSS (for creating the web interface)
Deployment: Local deployment (for development)
Model Training:
The model is trained on synthetic student data. The training process involves preprocessing grades and personal information, followed by training an SVM classifier to predict student performance.
License:
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing:
Feel free to fork the project, open issues, or submit pull requests for enhancements or bug fixes.

markdown
Copy code

### Tech Stack:
- **Backend**: Flask
- **Machine Learning**: Scikit-Learn (SVM, GridSearchCV, Preprocessing)
- **Email**: Flask-Mail (Gmail SMTP integration)
- **Frontend**: HTML, CSS (for basic interface)
- **Data Processing**: Pandas, NumPy
- **Model Serialization**: Joblib
- **Version Control**: Git, GitHub
