# Text-Classification-Using-IMDB-Dataset-form-Hugginface
Text Classification Using IMDB Dataset form Hugginface and saving and deploying model using pickle
## **Objective:**

In this project, we will develop a text classification model using data from Hugging Face. We will perform all steps from data loading to model training, and then deploy the model for inference in a new notebook.

### **Steps:**

1. **Data Loading:**
    - Choose a text classification dataset i.e. IMDB Dataset from Hugging Face Datasets
    - Load the dataset
    - Split the dataset into training, validation, and test sets.
2. **Data Preprocessing:**
    - Tokenize the text data
    - Convert the tokenized data into a format suitable for training
    - Create data loaders for the training, validation, and test sets.
3. **Model Training:**
    - Choose a classification model from sklearn Library
    - Train the model.
4. **Model Evaluation:**
    - Evaluate the trained model on the test set.
    - Performance metrics (e.g., accuracy, F1 score).
5. **Model Deployment:**
    - Save the trained model. (Joblib, Pickle)
    - Create a new Jupyter notebook for model deployment.
    - Load the saved model in the new notebook.
    - Write a function to take raw text input, preprocess it, and use the model to predict the class.
    - Test the deployed model with sample text inputs.
