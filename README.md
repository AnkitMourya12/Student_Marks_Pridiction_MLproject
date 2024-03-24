## Student Marks Prediction ML Project

### Overview

This machine learning project aims to predict the marks of students based on the number of study hours per day. The dataset used for training and testing the model consists of records from 200 university students.

### Dataset

- The dataset contains information on 200 students including their study hours and corresponding marks.
- Initially, the dataset contains 5 null values in the independent variable (study hours).

### Data Preprocessing

- The null values in the study hours column are replaced with the mean value of the study hours.
- This preprocessing step ensures that the dataset is clean and ready for model training.

### Model Training

- The machine learning model is trained using the processed dataset.
- We have used a pre-trained model saved in a file named "student_mark_predictor.pkl".
- The model predicts the marks based on the input study hours.

### Flask Web Application

- The Flask web application allows users to input their study hours and get predictions for their marks.
- The application is hosted locally and runs on port 8080.

### Files

- `app.py`: Contains the Flask web application code for predicting student marks.
- `index.html`: HTML template for the user interface of the web application.
- `student_mark_predictor.pkl`: Pre-trained machine learning model for predicting student marks.
- `smp_data_from_app.csv`: CSV file storing input study hours and predicted marks.

### Usage

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`
4. Open your web browser and go to `http://localhost:8080` to access the application.


### Additional Notes

- This project can be extended by incorporating more features such as previous academic performance, extracurricular activities, etc., for more accurate predictions.
- Continuous monitoring and improvement of the model's performance can be done by collecting additional data and retraining the model periodically.

---
