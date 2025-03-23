# Migraine Type Prediction

## Description

The **Migraine Type Prediction** app is designed to help identify different types of migraines based on user-inputted symptoms and characteristics. Using machine learning, specifically a Random Forest Classifier, the model predicts the type of migraine a user is likely to experience. Additionally, the app provides preventive measures tailored to each predicted migraine type.

This tool is useful for individuals suffering from migraines who wish to better understand their condition and take preventive actions based on their symptoms.

## Features

- **Migraine Type Prediction**: Predicts the type of migraine based on user input.
- **Personalized Preventive Measures**: Provides tailored preventive measures for different migraine types.
- **User-Friendly Interface**: Simple and intuitive interface built with Streamlit.
- **Data Preprocessing**: Handles missing values and encodes categorical features.
- **Model Training and Tuning**: A Random Forest Classifier is trained on the data and tuned using GridSearchCV for optimal performance.

## Technologies Used

- **Python**: Programming language used for developing the application.
- **Streamlit**: Web framework for creating the interactive interface.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: For machine learning (RandomForestClassifier, preprocessing, and model tuning).
- **Pickle**: For saving and loading the trained model.
- **Matplotlib**: For visualizations (optional for model evaluation).

## Example Output:
- Prediction: "Migraine without aura"
- Preventive measures:
    - Maintain regular sleep patterns.
    - Stay hydrated.
    - Identify and avoid trigger foods.
    - Manage stress.
