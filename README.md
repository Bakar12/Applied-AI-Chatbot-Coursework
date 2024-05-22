# ChatBot

This repository contains the `ChatBot.ipynb` notebook which is a part of an Applied AI Coursework. The notebook explores the application of AI techniques in the development of a chatbot.

## Overview

The notebook is divided into several sections:

1. **Part A – Application area review**: This section provides a comprehensive review of the application of chatbots in various fields. It discusses the history, types, and evolution of chatbots.

2. **Part B – Compare and evaluate AI techniques**: This section compares and evaluates various AI techniques used in chatbot development, such as Sentiment Analysis and Named Entity Recognition (NER).

3. **Input Data and Preprocessing**: This section discusses the preprocessing steps required for the input data before feeding it into the model.

4. **Prototype**: This section includes the implementation of a chatbot prototype. It covers the following steps:
    - Importing necessary libraries
    - Loading and preprocessing the data
    - Tokenisation and padding of sequences
    - Defining the model architecture
    - Training the model
    - Evaluating and visualising the model performance
    - Creating inference models
    - Interactive dialogue generation
    - Evaluation of the chatbot

5. **References**: This section lists all the references used in the notebook.

## Requirements

The notebook uses the following libraries:
- numpy
- tensorflow
- pandas
- matplotlib
- sklearn

## Data Files

This project requires a data file named `dialogs.txt` for its operation. This file contains the dialogues used by the chatbot for its responses.

### Dialogs.txt

The `dialogs.txt` file should be formatted as follows:

Each line represents a dialogue exchange, with the question and answer separated by a tab character (`\t`). The chatbot uses these dialogues to generate its responses.

Please ensure that this file is located in the same directory as your `ChatBot.ipynb` notebook for the code to function correctly.

## Usage

To use the notebook, clone the repository and open the `ChatBot.ipynb` file in your Jupyter notebook environment.

## Contributing

Contributions are welcome. Please open an issue to discuss the changes or open a pull request.
