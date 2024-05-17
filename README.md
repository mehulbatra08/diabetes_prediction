# Diabetes Prediction using Support Vector Machine (SVM)

This project involves predicting whether a person has diabetes based on their health data using a Support Vector Machine (SVM) classifier. The dataset used is the `diabetes.csv` file which contains various health metrics of patients.

## Dataset

The dataset consists of multiple health parameters such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- Outcome (0 or 1 indicating if the person has diabetes or not)

## Project Structure

The main steps involved in the project are:

1. Loading and exploring the dataset
2. Data preprocessing and standardization
3. Splitting the dataset into training and testing sets
4. Training the SVM classifier
5. Evaluating the model

## Getting Started

### Prerequisites

- Python 3.x
- Pandas
- NumPy
- scikit-learn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/diabetes-prediction.git
    ```
2. Navigate to the project directory:
    ```sh
    cd diabetes-prediction
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
