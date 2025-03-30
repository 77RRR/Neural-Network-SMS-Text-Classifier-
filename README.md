# Neural Network SMS Text Classifier

## Overview
This project is a machine learning model that classifies SMS messages as either "ham" (legitimate messages) or "spam" (unwanted advertisements or fraudulent messages). The classifier is built using a neural network and trained on the **SMS Spam Collection Dataset**.

## Dataset
- **Dataset Path**: `C:\Users\ranji\OneDrive\Desktop\MS Spam Collection Dataset\spam.csv`
- The dataset consists of labeled SMS messages categorized as `ham` or `spam`.

## Project Objectives
1. **Data Preprocessing**: Clean and preprocess the text data.
2. **Feature Extraction**: Convert text into numerical representations (e.g., TF-IDF or word embeddings).
3. **Model Training**: Train a neural network to classify messages.
4. **Prediction Function**: Implement `predict_message()` to classify new messages.
5. **Evaluation**: Assess model accuracy using test data.

## Installation & Usage
### Prerequisites
- Python 3.x
- Jupyter Notebook / Google Colaboratory
- Required Libraries: `pandas`, `numpy`, `sklearn`, `tensorflow`, `keras`, `nltk`

### Running the Project
1. Load the dataset and preprocess text.
2. Split the data into training and testing sets.
3. Train the model using a neural network.
4. Test the classifier on unseen messages.
5. Use `predict_message("your text here")` to classify new messages.

## Model Performance
- The model achieves high accuracy in distinguishing spam from ham messages.
- Evaluation is based on precision, recall, and F1-score.

## Future Improvements
- Implementing LSTM or Transformer-based models for better accuracy.
- Expanding dataset with more diverse spam messages.
- Deploying the model as a web service for real-time classification.

## Author
**Ranjeeth Kumar Patra** - Aspiring Data Scientist & Machine Learning Enthusiast

