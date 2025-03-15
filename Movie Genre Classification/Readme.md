# Movie Genre Classification

## Project Overview
The objective of this project is to develop a machine learning model that classifies movies into genres based on their descriptions. The model uses Natural Language Processing (NLP) techniques and machine learning algorithms to predict  genres associated with a given movie. The classification pipeline involves text preprocessing, feature extraction, model training, evaluation, and deployment.

## Key Features

- **Text Preprocession**: The data undergoes preprocessing steps like removing unnecessary values from the dataset for model training.

- **Model Training**: A TF-IDF vectorizer is combined with Logistic Regression to build the classification model. The dataset is split into training and testing sets for reliable performance evaluation.

- **Evaluation Metrics**: Model performance is assessed using accuracy score and a classification report.

- **Pipeline Saving**: The trained model, along with the vectorizer, is saved as a pickle file in the 'Model_Trained' directory for future use.

## Concepts Used
- **Natural Language Processing(NLP)**:
    - **Tokenization**: Splitting movie descriptions into words or phrases for further processing.
    - **Stop-word Removal**: Filtering out common words (e.g., "the," "and") to focus on meaningful content.
    - **TF-IDF (Term Frequency-Inverse Document Frequency)**: A numerical statistic used to convert textual data into a weighted feature representation, helping the model understand the importance of words in the dataset.

- **Machine Learning**:
    - **Logistic Regression**: A classification algorithm used to predict the probability of a movie belonging to one or more genres.
    - **Pipeline Management**: The entire NLP and classification workflow is encapsulated in a pipeline to ensure smooth training and prediction processes.


## Approach
- Data Loading & Preprocessing: Load movie descriptions from a JSON file and preprocess them by removing unnecessary values and applying TF-IDF vectorization.
- Feature Engineering: Convert text data into numerical vectors using TF-IDF.
- Model Training: Train a Logistic Regression model on the transformed data.
- Evaluation: Use accuracy score to assess model performance.
- Saving the Model: Store the trained pipeline in the Model_Trained directory for later use.


## Expected Outcomes
- A trained machine learning model capable of predicting movie genres with high accuracy.
- An automated and structured approach to movie genre classification.
- A saved and reusable model pipeline for further improvements and integrations.