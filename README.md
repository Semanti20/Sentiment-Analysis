# Sentiment-Analysis
This project performs sentiment analysis on a text review dataset using Python in Google Colab. It begins with data loading and exploration, followed by text preprocessing including tokenization and stop word removal. Sentiment scores are calculated using TextBlob. The data is then split into training and testing sets to train a neural network model to predict sentiment. The model's performance is evaluated using a confusion matrix and classification report. Finally, the project includes a function to predict the sentiment of user-provided text inputs, along with the sentiment score.

Approach:

Data Preprocessing: Text is cleaned by tokenizing and removing stop words.

Sentiment Scoring: TextBlob is used to calculate sentiment polarity scores.

Model Training: A neural network (LSTM) is trained on the data.

Model Evaluation: The model's performance is assessed using metrics like confusion matrix and classification report.

Prediction: A function predicts the sentiment of new text inputs.

Expected Outcomes:
A trained model for sentiment prediction.

Sentiment scores for text.

Model evaluation metrics and visualizations.

A function to predict sentiment from user input.

A text processing pipeline.

Tools and Technologies used:

Python: The primary programming language.

pandas: For data manipulation.

NLTK: For text processing (tokenization, stop word removal).

TextBlob: For sentiment analysis.

TensorFlow/Keras: For building and training the neural network model.

scikit-learn: For model evaluation (train/test split, confusion matrix, classification report).

matplotlib & seaborn: For data visualization.

Google Colab: The development environment.
