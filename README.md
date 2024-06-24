# Chatbot_Project_Vedika
A simple chatbot project using PyTorch and NLTK

# Chatbot Project - Vedika

This repository contains a simple chatbot named Vedika, developed using PyTorch and NLTK. The chatbot can respond to various user inputs based on pre-defined intents. It demonstrates basic natural language processing and machine learning techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Intents](#intents)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

## Project Overview
This project implements a basic chatbot using PyTorch for the neural network and NLTK for natural language processing. The chatbot, named Vedika, can understand user inputs and respond appropriately based on predefined intents.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- numpy
- nltk
- torch

You can install these libraries using pip:

pip install numpy nltk torch

## Usage

Clone the repository:
git clone https://github.com/your-username/Chatbot_Project_Vedika.git
cd Chatbot_Project_Vedika

Run the chatbot:
python chatbot.py


## Model Training
The training script is included in the chatbot.py file. It loads the training data from intents.json, preprocesses it, and trains a neural network to classify the intents.

## Hyperparameters
Number of epochs: 800
Batch size: 8
Learning rate: 0.0001
Hidden size: 16

## Training Data
The training data is provided in the intents.json file. Each intent contains patterns and responses. The patterns are used to train the model, and the responses are used to reply to the user.

## Training Process
Tokenize the patterns.
Stem the words.
Create a bag of words for each pattern.
Train a neural network using PyTorch.

## Intents
The intents.json file contains various intents with the following structure:

{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["Hi", "Hello", "Good morning"],
      "responses": ["Hello!", "Hi there!", "Greetings!"]
    },
    ...
  ]
}
This file defines the conversational patterns and the corresponding responses.

## Technologies Used
Python: The main programming language used.
PyTorch: For building and training the neural network.
NLTK: For natural language processing tasks such as tokenization and stemming.
NumPy: For numerical operations and array handling.

## Acknowledgements
This project is based on tutorials and examples from various sources. Special thanks to the open-source community for their valuable contributions.
