# Heart Attack Predictor

## Introduction

This project is a Heart Attack Predictor that leverages machine learning algorithms to predict the likelihood of a heart attack based on various medical and demographic factors. The dataset underwent extensive data preprocessing using Pandas and NumPy, followed by feature engineering to enhance the model's predictive power. Multiple algorithms were tested, including Linear Regression, Decision Tree, Support Vector Regression (SVR), and Random Forest, to determine the best-performing model. The final model was then deployed as a web application using Flask, with an interface designed using HTML and CSS.

## Project Structure

- `data/`: Contains the dataset used for training and testing the models.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, feature engineering, and model evaluation.
- `app/`: Flask application files, including HTML templates and CSS stylesheets.
- `models/`: Serialized model files for deployment.
- `static/`: Static files for CSS, JavaScript, and images.
- `templates/`: HTML templates for the web application.
- `app.py`: Main Flask application file.
- `requirements.txt`: List of Python dependencies.

## Data Preprocessing

Data preprocessing was performed using Pandas and NumPy. Key steps included:

- Handling missing values.
- Encoding categorical variables.
- Scaling numerical features.
- Splitting the data into training and testing sets.

## Feature Engineering

Feature engineering was crucial for improving model performance. Techniques included:

- Creation of new features based on domain knowledge.
- Selection of important features using correlation analysis and feature importance metrics.

## Algorithms Used

The following machine learning algorithms were tested:

1. **Linear Regression**: A basic regression algorithm used as a benchmark.
2. **Decision Tree**: A tree-based algorithm that splits the data based on feature importance.
3. **Support Vector Regression (SVR)**: A regression technique that uses a margin of tolerance.
4. **Random Forest**: An ensemble method that combines multiple decision trees to improve accuracy.

After evaluating these models, the Random Forest algorithm was chosen as the best-performing model for this task.

## Web Application

The final model was deployed as a web application using Flask. The front end of the application was developed using HTML and CSS, providing an intuitive user interface where users can input relevant medical data and receive a prediction on the likelihood of a heart attack.

## Future Scope

- **Improved Model Performance**: Experimenting with more advanced algorithms like XGBoost or neural networks could further enhance prediction accuracy.
- **User Authentication**: Adding a user authentication system to save and track predictions over time.
- **Real-time Data**: Integrating real-time data collection from wearable devices for dynamic prediction updates.
- **Deployment**: Deploying the application on a cloud platform like AWS or Heroku for wider accessibility.
- **Mobile Application**: Developing a mobile version of the web application for better usability and accessibility on mobile devices.

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
      git clone https://github.com/amitmaji01/Heart_attack_classifier
