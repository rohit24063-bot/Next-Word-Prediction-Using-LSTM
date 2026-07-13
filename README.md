
# Next Word Prediction Using LSTM

This project implements a next-word prediction model using a Long Short-Term Memory (LSTM) neural network. The model takes a sequence of words as input and predicts the most likely next word.

An interactive web application was developed using Streamlit to allow users to test the trained model.

## Live Demo

[Try the application here](next-word-prediction-using-lstm-cziq4y2cvuoz2yv7wgj83f.streamlit.app)

## Features

- Predicts the next word from user-provided text
- Uses an LSTM neural network for sequence prediction
- Interactive user interface built using Streamlit
- Uses a saved tokenizer for text preprocessing
- Performs sequence padding before prediction

## Technologies Used

- Python
- TensorFlow
- Keras
- LSTM
- NumPy
- Streamlit
- Natural Language Processing

## Project Structure

```text
Next-Word-Prediction-Using-LSTM/
│
├── app.py
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── requirements.txt
└── README.md
