# Amazon Product Rating Prediction Using LSTM

## Project Overview
This project aims to predict Amazon product ratings using product information and customer reviews. It uses Deep Learning techniques, particularly Long Short-Term Memory (LSTM), to learn patterns in review text and predict numerical ratings.

## Objectives
- Preprocess customer review data.
- Convert text into numerical sequences using tokenization and padding.
- Build and train an LSTM-based Deep Learning model.
- Predict product ratings from review text.
- Evaluate model performance by comparing actual and predicted ratings.

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- Pandas and NumPy
- Scikit-learn
- Matplotlib

## Model Architecture
1. **Embedding Layer:** Converts words into numerical vector representations.
2. **LSTM Layer:** Learns patterns and context from review text.
3. **Dropout Layer:** Helps reduce overfitting.
4. **Dense Layer:** Learns patterns for the final prediction.
5. **Output Layer:** Predicts a numerical rating using linear activation.

## Methodology
1. Load the dataset.
2. Clean and preprocess the data.
3. Tokenize and pad the review text.
4. Split the dataset into training and testing sets.
5. Train the LSTM model.
6. Predict ratings on the test data.
7. Evaluate predictions using MAE, RMSE, and R² score.

## Evaluation Metrics
- **MAE:** Measures the average absolute difference between actual and predicted ratings.
- **RMSE:** Measures prediction error while penalizing larger errors.
- **R² Score:** Measures how well the model explains rating variation.

## Future Enhancements
- Train and evaluate using a larger real-world Amazon reviews dataset.
- Improve performance through hyperparameter tuning.
- Test predictions on new customer reviews.
- Develop a simple web application for rating prediction.

## Conclusion
This project demonstrates how Deep Learning and text processing can be used to predict product ratings from customer reviews. It provides practical experience in data preprocessing, LSTM model development, training, and evaluation.

## Author
Gopika Sasikumar
