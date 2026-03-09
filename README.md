IMDB Sentiment Analysis using LSTM

This project performs sentiment analysis on movie reviews using a Long Short-Term Memory (LSTM) neural network built with TensorFlow/Keras.

The model predicts whether a movie review is positive or negative.

⸻

Dataset

Dataset used: IMDB Movie Reviews Dataset
	•	50,000 movie reviews
	•	Binary sentiment classification (Positive / Negative)

⸻

Technologies Used
	•	Python
	•	TensorFlow / Keras
	•	Pandas
	•	NumPy
	•	Scikit-learn

⸻

Project Workflow
	1.	Load IMDB dataset
	2.	Preprocess text data
	3.	Tokenize reviews into sequences
	4.	Apply sequence padding
	5.	Train LSTM model
	6.	Evaluate model performance
	7.	Predict sentiment for new reviews

⸻

Model Architecture

Embedding Layer
↓
LSTM Layer
↓
Dense Output Layer (Sigmoid)

⸻

Example Prediction

Input review:

“This movie was amazing and I loved the acting.”

Prediction:

Positive

