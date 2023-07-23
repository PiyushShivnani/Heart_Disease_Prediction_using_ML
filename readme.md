# Heart Disease Prediction


Welcome to the Heart Disease Prediction project! This repository contains a Python script for predicting heart disease using various machine learning models. The dataset used for this project is named `Heart_Disease_Prediction.csv`.

## Dataset Description

The dataset contains essential attributes related to heart health. These attributes are used to predict the presence or absence of heart disease in individuals. The columns in the dataset include:

- `age`: Age of the individual (in years).
- `gender`: Gender of the individual (1 for male, 0 for female).
- `chest pain type`: Type of chest pain experienced by the individual (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic).
- `resting blood pressure`: Resting blood pressure of the individual (in mm Hg).
- `serum cholestoral`: Serum cholestoral level in mg/dl.
- `fasting blood sugar > 120 mg/dl`: Whether fasting blood sugar is greater than 120 mg/dl (1 for yes, 0 for no).
- `resting electrocardiographic results`: Resting electrocardiographic results (values 0, 1, 2).
- `maximum heart rate achieved`: Maximum heart rate achieved during exercise.
- `exercise induced angina`: Whether exercise induced angina (1 for yes, 0 for no).
- `oldpeak`: ST depression induced by exercise relative to rest.
- `the slope of the peak exercise ST segment`: Slope of the peak exercise ST segment.
- `number of major vessels (0-3) colored by flourosopy`: Number of major vessels colored by flourosopy (0-3).
- `thalassemia`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect).

The target variable is `Heart Disease`, which is binary (1 for presence, 0 for absence).

## Required Libraries

This project utilizes various Python libraries to carry out data processing and machine learning tasks:

- `numpy`: Numerical computing library for Python.
- `pandas`: Data manipulation and analysis tool.
- `scikit-learn`: Machine learning library for Python.
- `matplotlib`: Data visualization library for Python.

## Model Building

The script employs five different machine learning models for heart disease prediction:

1. K-Nearest Neighbors (KNN) Classifier
2. Logistic Regression Classifier
3. Decision Tree Classifier
4. Random Forest Classifier
5. Multi-layer Perceptron (Neural Network) Classifier

The models are trained and tested using the dataset after preprocessing, which includes standard scaling of the features.

## How to Use

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/heart-disease-prediction.git
```

2. Install the required libraries using `pip`:

```
pip install numpy pandas scikit-learn matplotlib
```

3. Navigate to the project directory and run the Python script:

```
cd heart-disease-prediction
python heart_disease_prediction.py
```

4. The script will display the accuracies of all the models and select the best performing model.

5. After that, you will be prompted to enter values for the features to predict heart disease for a new individual.


## Contributions

We warmly welcome contributions to the Heart Disease Prediction project. Whether you spot any issues or have insightful ideas for enhancing the prediction system, we encourage you to engage with us by opening an issue or submitting a pull request on GitHub.

To ensure seamless collaboration, please adhere to the best practices and guidelines for Python development. Prioritize thorough testing of your changes to ensure their accuracy and reliability. Additionally, when committing your code, strive to provide clear and concise commit messages for improved code readability and project maintenance.

## Acknowledgments

We would like to express our gratitude to all contributors and users of this Heart Disease Prediction project. Please note that this system is designed as a demonstration project and not intended for production use. It was created to demonstrate fundamental Python programming concepts and to serve as a foundation for building more complex prediction systems.

Feel free to explore, learn from, and extend the code to suit your specific needs. We hope you find this project informative and a valuable resource for further Python development endeavors.

Happy coding!