# Aries_PDF_Answering
Creating a README file for your GitHub repository is essential for providing information about your project, its purpose, how to use it, and any other relevant details. Here's a suggested content structure for your README based on the PDF question answering application you've developed:

---

# PDF Question Answering with Streamlit

This is a simple application built with Streamlit that allows users to upload a PDF file and ask questions about its content. The application utilizes PyMuPDF for PDF processing and Hugging Face's Transformers library for question-answering capabilities.

## Features

- Upload a PDF file.
- Extract text from the uploaded PDF.
- Ask questions about the extracted text.
- Get answers to the questions using a pre-trained question-answering model.

## Technologies Used

- Python
- Streamlit
- PyMuPDF (fitz)
- Hugging Face Transformers

## Installation

To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Its-uks/pdf_answering.git
   cd pdf_answering
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run streamlit_app.py
   ```

## Usage

1. Upload a PDF file by clicking on "Upload a PDF file" button.
2. Once the text is extracted, ask a question in the text input field provided.
3. The application will provide the answer to your question based on the content of the PDF.
   

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
