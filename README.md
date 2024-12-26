# English-Spanish Translation System

## Project Overview
This project is a machine translation system capable of translating text and PDF documents between English and Spanish. Users can upload a PDF or input text directly, and the system will provide translations in the desired language.

The system leverages the **MarianMT model**, a state-of-the-art machine translation framework, for accurate and efficient translations.

---

## Features
- **Text Translation**: Translate sentences or paragraphs between English and Spanish.
- **PDF Upload and Translation**: Upload PDF files to extract and translate their contents.
- **Bidirectional Translation**: Supports translations from English to Spanish and vice versa.
- **User-Friendly Interface**: Simple workflow for uploading files and retrieving translations.

---

## Technologies Used
- **Model**: MarianMT (Hugging Face Transformers)
- **Programming Language**: Python
- **Libraries**:
  - `transformers` (for MarianMT model)
  - `PyPDF2` (for PDF text extraction)
  - `nltk` (for preprocessing and tokenization)

---

## How It Works
1. **Text Input**:
   - Users can enter text into a text box for translation.
   - The system detects the input language and translates it to the target language.

2. **PDF Upload**:
   - Users upload a PDF file.
   - Text is extracted from the PDF and passed to the MarianMT model for translation.

3. **Output**:
   - The translated text is displayed on the screen or saved as a downloadable file.

---

## Preprocessing Steps
- Tokenization using NLTK.
- Cleaning the dataset by removing unnecessary punctuation.
- Handling special tokens (<sos>, <eos>) for improving translation consistency.

---

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/translation-system.git
   cd translation-system
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

---

## Example Usage
- **Input**:
  - English: "How are you?"
  - Spanish: "¿Cómo estás?"

- **Output**:
  - Spanish: "¿Cómo estás?"
  - English: "How are you?"

- **PDF Translation**:
  - Uploaded: `sample.pdf`
  - Translated Text: Provided as downloadable content.

---

## Future Enhancements
- Add support for additional languages.
- Improve the user interface for seamless interaction.
- Enhance PDF parsing for complex documents.

---

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments
- Hugging Face for the MarianMT model.
- NLTK and PyPDF2 for their robust libraries.

