Sinhala Spell and Grammar Checker (LSTM, RAG, and Rule-based Models)
This repository contains the implementation of a Sinhala Spell and Grammar Checker using three different models: Rule-based Model, RAG Model, and LSTM Model. The project aims to automatically detect and correct spelling and grammar errors in Sinhala text, leveraging machine learning and traditional methods to enhance the quality and accuracy of written Sinhala.

Models:
Rule-based Model:

A simple rule-based approach to detect common spelling errors by checking words against a predefined dictionary. This model provides basic correction capabilities based on exact matches and string similarity techniques.
RAG Model:

A hybrid model combining retrieval-augmented generation (RAG) with a large dataset of Sinhala text. This model uses advanced methods to retrieve contextually relevant data and generate grammar suggestions or corrections.
LSTM Model:

A Long Short-Term Memory (LSTM)-based deep learning model that learns long-term dependencies in text sequences for both spell correction and grammar improvement. This model is trained on a labeled dataset of Sinhala sentences and provides high accuracy in both spelling and grammar correction tasks.
Features:
Spell Correction: Detects misspelled words and suggests the closest possible correct alternatives.
Grammar Suggestions: Identifies grammatical errors such as subject-verb agreement issues and sentence structure errors and provides suggestions for improvement.
Multi-model Comparison: Compare the effectiveness of the Rule-based, RAG, and LSTM models for spelling and grammar correction tasks in Sinhala text.
Technologies Used:
Python: The main programming language used to implement the models.
TensorFlow/Keras: For building and training the LSTM-based deep learning model.
Scikit-learn: For data preprocessing and evaluation.
Difflib: For spell correction using string matching.
Word Documents: For loading Sinhala dictionary data for spell correction.
Evaluation Metrics:
Accuracy: The LSTM model achieved an accuracy of 96% in classifying and correcting spelling and grammar errors.
Precision, Recall, F1-Score: The model also shows impressive precision and recall rates, ensuring reliable corrections for both spelling and grammar.
