# HealthCare ChatBot

The HealthCare ChatBot is a Python script that utilizes machine learning to predict diseases based on given symptoms. It incorporates a Decision Tree classifier and Support Vector Machine (SVM) for prediction. Additionally, it employs a chat-like interaction for collecting symptom information from the user.

## Code Overview

The code includes data loading and preprocessing steps, the creation and training of machine learning models (Decision Tree and SVM), and functions for implementing a chatbot-like interaction to predict diseases based on user-input symptoms.


Note: The code provides a user-friendly interface for predicting diseases, making it accessible and informative for users.

## Documentation

[Python](https://docs.python.org/3/) 
[Pandas](https://pandas.pydata.org/docs/)
[NumPy](https://numpy.org/doc/stable/)
[scikit-learn (sklearn)](https://scikit-learn.org/stable/)
[pyttsx3](https://pyttsx3.readthedocs.io/en/latest/)


## How to Run

1. Ensure required libraries are installed (`pandas`, `numpy`, `sklearn`, `pyttsx3`).
2. Provide the path to the 'Training.csv' and 'Testing.csv' files.
3. Run the script.
4. The chatbot will interactively ask for symptoms and provide predictions and information about possible diseases.
## Features

The HealthCare ChatBot comes with a set of features to enhance user experience and provide valuable health-related information.

- Disease Prediction

The primary functionality of the chatbot is to predict diseases based on user-input symptoms. It utilizes a trained Decision Tree classifier and Support Vector Machine (SVM) for accurate predictions.

- Interactive Symptom Collection

The chatbot engages users in an interactive conversation to collect information about their symptoms. Users are prompted to input symptoms, and the chatbot responds dynamically, guiding them through the process.

- Severity Information

The chatbot provides severity information related to symptoms. It calculates the severity of symptoms based on user inputs and recommends appropriate actions, such as consulting a doctor or taking precautions.

- Symptom Descriptions

Users can get detailed descriptions of symptoms associated with predicted diseases. The chatbot fetches information from external sources to provide a comprehensive overview of the identified health issues.

- Precautionary Measures

For each predicted disease, the chatbot offers precautionary measures to be taken. These measures are crucial for users to understand how they can manage and prevent the identified health condition.

- Text-to-Speech Capability

The chatbot is equipped with text-to-speech functionality using the `pyttsx3` library. It can read out information, making it more accessible for users with different preferences.

- Cross-Validation Scores

The chatbot calculates and displays cross-validation scores for the machine learning models, giving users insights into the reliability of the disease predictions.

- User-Friendly Interface

The chatbot provides a friendly and conversational interface, making it easy for users to interact with the system. It asks questions, provides information, and guides users through the entire process.

- Robust Data Handling

The code handles data efficiently, loading training and testing datasets, preprocessing features, and splitting data for training and testing machine learning models.

## Authors

- [@RottenBanana420](https://github.com/RottenBanana420)
- [@Hrishhiii](https://github.com/Hrishhiii)


