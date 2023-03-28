# ChatGPT-PDF_Reader_Streamlit
ChatGPT_PDF_Reader_Streamlit is a Python program that uses the OpenAI ChatGPT model to generate answers to user questions from a PDF file. The program is built using the Streamlit framework, which provides a simple and intuitive web interface for the user to upload a PDF file and enter questions.

The program starts by prompting the user to enter their OpenAI API key, which is used to access the ChatGPT model. The user is then presented with a file uploader widget, where they can select a PDF file to analyze. Once the file is uploaded, the program extracts the text from the PDF using the PyPDF2 library and stores it in a variable.

The user can then enter a question in a text input widget. The program uses the ChatGPT model to generate an answer to the question, based on the text extracted from the PDF file. The answer is displayed to the user in a text output widget.
