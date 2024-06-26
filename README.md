# Disease Prediction App

This repository contains a web application for predicting the likelihood of three diseases: Parkinson's, heart disease, and diabetes. The application is built using Streamlit and utilizes machine learning models trained in Python.

## Features

- Predicts the likelihood of Parkinson's, heart disease, and diabetes.
- User-friendly interface built with Streamlit.
- Real-time predictions based on user input.
- Deployed on Heroku for easy accessibility.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Streamlit
- Scikit-learn
- Pandas
- Numpy

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/disease-prediction-app.git
    cd disease-prediction-app
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the App

To run the application locally, use the following command:
```bash
streamlit run app.py
```
### Project Structure

disease-prediction-app/
│
├── models/
│   ├── parkinsons_model.pkl
│   ├── heart_disease_model.pkl
│   └── diabetes_model.pkl
│
├── app.py
├── requirements.txt
└── README.md


