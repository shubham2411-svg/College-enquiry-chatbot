## College Inquiry Chatbot System - README
## Overview
This repository contains the code for a chatbot system designed to answer queries related to a college.
The chatbot uses Natural Language Processing (NLP) and a deep learning model built with TensorFlow's Keras library. 
The system can recognize intents from user inputs and provide appropriate responses based on predefined patterns.

## Prerequisites
Python 3.x
The following Python packages:
nltk
tensorflow
numpy
pickle

## Installation
Ensure you have Python 3.x installed on your machine. You can download it from the official Python website.
Install the required packages using pip:
pip install nltk tensorflow numpy

## Preparing the Data
Create an intents.json file that contains your chatbot intents, patterns, and responses. Here is an example structure:
Place the intents.json file in the same directory as your script.

## Running the Script
Run the script to preprocess the data, create training sets, and train the model:
The script will process the intents, tokenize and lemmatize the text, and create a bag of words model for training.
The trained model will be saved as chatbotmodel.h5 and the processed data will be saved as words.pkl and classes.pkl.
