# Multiple Disease Prediction System using Machine Learning


![Screenshot from 2023-11-25 15-08-50](https://github.com/govindvarma1/multiple-disease-prediction/assets/98372421/0ff34786-0edc-49f0-93b2-af5a6092c4f7)
![Screenshot from 2023-11-25 15-08-56](https://github.com/govindvarma1/multiple-disease-prediction/assets/98372421/04baf337-c093-4700-a13b-4d3c7c88982d)
![Screenshot from 2023-11-25 15-09-00](https://github.com/govindvarma1/multiple-disease-prediction/assets/98372421/dc712577-253f-4aef-847a-1fbbe175b36a)



This project provides a streamlit web application for predicting multiple diseases, including diabetes, Parkinson's disease, and heart disease, using machine learning algorithms. The prediction models are deployed using Streamlit, a Python library for building interactive web applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Multiple Disease Prediction project aims to create a user-friendly web application that allows users to input relevant medical information and receive predictions for different diseases. The machine learning models trained on disease-specific datasets enable accurate predictions for diabetes, Parkinson's disease, and heart disease.

## Features

The Multiple Disease Prediction web application offers the following features:

- **User Input**: Users can input their medical information, including age, gender, blood pressure, cholesterol levels, and other relevant factors.
- **Disease Prediction**: The application utilizes machine learning models to predict the likelihood of having diabetes, Parkinson's disease, and heart disease based on the inputted medical data.
- **Prediction Results**: The predicted disease outcomes are displayed to the user, providing an indication of the probability of each disease.
- **Visualization**: Visualizations are generated to highlight important features and provide insights into the prediction process.
- **User-Friendly Interface**: The web application offers an intuitive and user-friendly interface, making it easy for individuals without technical knowledge to use the prediction tool.

## Setup

To use this project locally, follow these steps:

1. Clone the repository:

```bash
git https://github.com/govindvarma1/multiple-disease-prediction
```

2. Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

3. Download the pre-trained machine learning models for diabetes, Parkinson's disease, and heart disease. Make sure to place them in the appropriate directories within the project structure.

4. Update the necessary configurations and file paths in the project files.

## Usage

To run the Multiple Disease Prediction web application, follow these steps:

1. Open a terminal or command prompt and navigate to the project directory.

2. Run the following command to start the Streamlit application:

```bash
streamlit run multiplediseaseprediction.py
```

3. Access the web application by opening the provided URL in your web browser.

4. Input the relevant medical information as requested by the application.

5. Click the "Predict" button to generate predictions for diabetes, Parkinson's disease, and heart disease based on the provided data.

6. View the prediction results and any accompanying visualizations or insights.

Feel free to customize the web application's appearance, add more disease prediction models, or integrate additional features based on your specific requirements.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify and use the code for both personal and commercial purposes.
