# POS-TAGGING
Part-of-Speech Tagging using Deep Learning Models

# Description:
This GitHub repository contains the code implementation for Part-of-Speech (POS) tagging using Natural Language Processing (NLP) techniques. The code is organized as part of a laboratory assignment (Lab 8) undertaken by Tarush Singh (E21CSEU0974) as part of the Natural Language Processing course.

# Overview:
Objective: The code aims to perform POS tagging, a fundamental task in NLP, using various techniques and models.
Libraries: The implementation utilizes TensorFlow and NLTK for deep learning and NLP functionalities.
Datasets: The code loads and preprocesses tagged corpora from NLTK, including the Treebank, Brown, and CoNLL 2000 corpora.

# Models Implemented:
A baseline LSTM-based POS tagging model.
A Bidirectional LSTM model for enhanced performance.
Integration of pre-trained word embeddings (GloVe) for improved word representations.
# Steps:

# 1) Data Preprocessing:

The code preprocesses the tagged sentences, extracts words and POS tags, and creates vocabulary and POS tag sets.
It converts words and POS tags to numerical indices and performs padding for consistent sequence lengths.

# 2) POS Model Architecture:

The initial model is a Sequential model with an Embedding layer, LSTM layer, dropout, and TimeDistributed dense layer for each time step.The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.

# 3) Model Training:
The model is trained on the provided datasets, and training progress is visualized using matplotlib.

# 4 )Model Evaluation:
The model is evaluated on the test set, and metrics such as classification report and confusion matrix are presented.

# 5) Fine-Tuning:
The code explores fine-tuning steps, including a Bidirectional LSTM model and integration of pre-trained word embeddings (GloVe).

# 6) Visualizations:
Training processes and accuracies are visualized for both the baseline and fine-tuned models.

# 7) Results:
The code presents the performance metrics, including accuracy, precision, recall, and F1 score, for each model.

# 8) Conclusion:
The repository provides a comprehensive exploration of POS tagging techniques in NLP, showcasing different model architectures and fine-tuning approaches.

# -> Instructions:
Ensure TensorFlow and NLTK are installed using the provided pip install commands.
Run the code cells in sequential order for a step-by-step execution.
Feel free to explore, experiment, and contribute to the enhancement of POS tagging techniques in NLP!
