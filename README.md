📺 Netflix Sentiment Analysis using Neural Networks
📌 Overview

This project applies Natural Language Processing (NLP) and Neural Networks to perform sentiment analysis on Netflix reviews.
The model classifies user reviews into positive, negative, or neutral sentiments, helping understand audience opinions and improving recommendation systems.

📂 Dataset

Contains Netflix reviews with text and labeled sentiment.

Preprocessing steps include:

Tokenization & text cleaning

Stopword removal

Sequence padding for uniform length

Label encoding (Positive, Negative, Neutral)

🧠 Model Architecture

The model is implemented using Keras & TensorFlow with the following layers:

Embedding Layer: Converts words into dense vector representations

LSTM Layer: Captures sequential dependencies in reviews

Dense Layers: Fully connected layers for classification

Output Layer: Softmax activation for multi-class sentiment prediction

Loss Function: Categorical Crossentropy
Optimizer: Adam

📊 Results

Achieved 85–90% accuracy on the test set

Training & validation accuracy/loss plotted for performance monitoring

Example Predictions:

“I loved this series!” → Positive

“It was boring and terrible.” → Negative

“The show was okay, not too great.” → Neutral

🚀 Applications

Entertainment Industry → Analyze audience reviews automatically

E-commerce → Product review classification

Social Media Monitoring → Detect customer sentiment in real-time

Technologies Used

Python

Pandas, NumPy

TensorFlow / Keras

Matplotlib, Seaborn

scikit-learn
