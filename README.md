English-Spanish Machine Translation System

Overview

This project is a Machine Translation System designed to translate text between English and Spanish, and vice versa. The system provides users with the ability to:

Translate plain text.

Upload PDF documents for translation.

The application leverages modern natural language processing (NLP) techniques and machine learning models to deliver accurate and context-aware translations.

Features

1. Text Translation

Users can input text directly into the system to receive translations between English and Spanish.

2. PDF Upload and Translation

Users can upload PDF documents.

Extracts text from the PDF and translates it into the target language while preserving the original format.

3. User-Friendly Interface

Intuitive and easy-to-use interface.

Supports both text area input and file uploads for convenience.

Technology Stack

1. Programming Language

Python: For implementing the backend and model logic.

2. Machine Learning Frameworks

Hugging Face Transformers: Used for training and fine-tuning the MarianMT model for English-Spanish translation.

3. Libraries

NLTK: For text preprocessing, such as tokenization and cleaning.

PyPDF2: For extracting text from PDF documents.

streamlite: For creating a web interface (choose one based on preference).

Preprocessing Steps

Text Cleaning: Removal of special characters, punctuation, and unnecessary whitespace.

Tokenization: Breaking down sentences into tokens for better model input.

Language Tags: Ensures input and output languages are explicitly defined for model translation.

Model Training

Dataset: Utilized a parallel corpus (CSV format) containing aligned English-Spanish sentences.

Sequence Length: Limited to 20 tokens for efficient training.

Training Library: Hugging Face Trainer was used for optimizing the model.

Usage

1. Text Translation

Input text in the designated text area.

Select the target language (English or Spanish).

Click "Translate" to get the translated text.

2. PDF Translation

Upload a PDF document.

Select the target language.

The translated document will be available for download in the same format.

Future Enhancements

Support for Additional Languages: Expand the system to include more language pairs.

Real-Time Translation: Integrate live translation for audio and video streams.

Improved Formatting: Enhance the PDF translation to better retain formatting and layout.

How to Run

Clone the repository:

git clone https://github.com/username/repository-name.git

Install dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Access the application in your browser at http://127.0.0.1:5000.

Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.
