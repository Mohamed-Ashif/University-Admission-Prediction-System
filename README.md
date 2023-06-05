
# University Admission Prediction Using Machine Learning Flask Webapp

This project is a Flask web application that predicts the likelihood of admission to a university based on various factors using machine learning. The application provides a user-friendly interface where users can enter their academic details and get an estimate of their chances of being accepted into a university.

![istockphoto-1332389695-612x612](https://github.com/Mohamed-Ashif/University-Admission-Prediction-System/assets/78372127/64551c9b-0ace-4f76-a9b0-f42cf7371240)

## Dataset

This dataset contains under given important parameters which are considered mainly during application for Masters Programs. The main aim of the data is to predict the chances of getting admission into a particular university, according to the "Chance of Admit" column which is ranging from 0 to 1.


## Attributes Information

■ GRE Scores ( out of 340 )

■ TOEFL Scores ( out of 120 )

■ University Rating ( out of 5 )

■ Statement of Purpose (SOP) Strength ( out of 5 )

■ Letter of Recommendation (LOR) Strength ( out of 5 )

■ Undergraduate GPA-CGPA ( out of 10 )

■ Research Experience ( either 0 or 1 )

■ Chance of Admit ( ranging from 0 to 1 )

## Requirements

To run the flask web application and reproduce the results of this project, the following dependencies are required:

◉ Python 3.9

◉ NumPy

◉ Pandas

◉ Scikit-learn

◉ Pickle

◉ Flask

## Project Structure

The project consists of the following files:

1. Admission_Predict.csv: The dataset file containing the features and target variable.

2. Predicting_Chance_of_Admission.ipynb:  Python script that includes the code for data preprocessing, model training, evaluation, and prediction.

3. finalized_model.pkl: It is a saved machine learning model file, potentially used for University Admission prediction, with the ".pkl" extension commonly associated with serialized models in Python.

4. app.py: Python script that includes the code for the Flask application.

5. templates/: A directory that contains HTML templates for the user interface of the web application.

   ◉ index.html: The main template file that displays the input form and prediction results.

◉ base.html: The base template file that provides the common structure and layout for other templates.

◉ results.html: The template file that displays the admission prediction results.

6. static/css: A directory that contains static assets such as CSS file for styling and interactivity.

◉  style.css: The CSS file that defines the styles and layout of the web application.

7. requirements.txt: This file lists the external dependencies and their versions for a Python project, facilitating easy installation of the required packages.

8. README.md: Project documentation providing an overview of the project and instructions.

## Instructions

1. Install the required dependencies mentioned in the "Requirements" section.

2. Clone or download the project repository.

3. Open the Predicting_Chance_of_Admission.ipynb file.

4. Follow the code to preprocess the data, train the ML model, evaluate its performance, and make predictions.

5. Save the ml model into finalized_model.pkl file for webapp prediction.

6. Run the script using the command python app.py.

7. Once the script is running, it will launch a Flask application locally.

8. Access the Flask application in your web browser at the provided URL.

9. Use the interactive interface to input the necessary data for predicting the likelihood of University Admission Chance.

10. The application will display the prediction results.


## Screenshot

![Final_Result](https://github.com/Mohamed-Ashif/University-Admission-Prediction-System/assets/78372127/be489224-0b9b-4109-bb7c-64f47fb3c788)


## Conclusion

The "University Admission Prediction System Using Machine Learning" is a Flask web application that predicts the likelihood of admission to a university based on various factors. It provides users with an intuitive interface to input their academic details and obtain an estimate of their chances of being accepted into a university.

