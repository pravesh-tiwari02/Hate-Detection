# Hate-Detection
Toxicity Analysis System

Overview

Our toxicity analysis system is designed to process social media posts and determine whether they contain harmful content. It categorizes posts based on six different toxicity labels: toxic, severe toxic, obscene, threat, insult, and identity hate. This tool aims to assist in moderating online interactions and fostering a safer digital environment.

Setup Guide

Follow these steps to install and run the system:

Ensure Python and Jupyter Notebook are installed on your computer.

Obtain the training dataset from Kaggle.

Download or clone this repository to your local machine.

Open the analysis.ipynb notebook in Jupyter Notebook.

Follow the guided steps in the notebook to train the model and analyze text.

How It Works

Once the system is set up, users can input any social media text for evaluation. The model will classify the text into the appropriate toxicity categories and return an analysis of its content.

Dataset Information

This project leverages the Jigsaw Toxic Comment Classification dataset from Kaggle, which contains Wikipedia discussion comments labeled with various types of toxicity.

Model Performance

We experimented with different architectures to enhance classification accuracy:

Model Version 1 (model_v1.py)

Accuracy: 93.75%

Precision: 50%

Neural Network Layers: 7

Model Version 2 (model_v2.py)

Accuracy: 98.95%

Precision: 75%

Neural Network Layers: 11

Further optimizations in the neural network structure can improve accuracy and precision.

Repository Contents

model_v1.py: Initial model implementation.

model_v2.py: Improved model with enhanced accuracy.

results.txt: Sample predictions. Example:

Input Tweet: "I'll harm you soon."

Toxic: True

Severe Toxic: False

Obscene: False

Threat: True

Insult: False

Identity Hate: False

Contributing

We welcome contributions! Feel free to fork the repository, propose improvements, and submit a pull request.
