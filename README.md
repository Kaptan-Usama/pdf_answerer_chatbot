# PDF Question Answerer 📄

## Overview
PDF Question Answerer is a Python-based tool that uses the power of OpenAI's GPT-3 model to answer questions about the content of PDF files. It merges all PDF files in a specified folder into one file, extracts the text, and uses GPT-3 to generate answers to user-inputted questions.

## How to Use
1. Enter your OpenAI API key in the sidebar.
2. Enter the path to a folder containing your PDF files.
3. The tool will merge all PDFs into one file.
4. Ask a question related to the content.
5. Get an automatically generated answer!

## Requirements
- Python 3.x
- Streamlit
- PyPDF2
- OpenAI
- docx2txt
- pyperclip

## Installation
1. Clone this repository.
2. Install the required packages using pip:
```
pip install -r requirements.txt
```
4. Run the Streamlit app:
```
streamlit run app.py
```


## Note
The accuracy of the answers depends on the quality of the text extraction from the PDF and the performance of the GPT-3 model. Also, remember to keep your OpenAI API key secure and not share it with others.

## License
This project is Open Sourse.
