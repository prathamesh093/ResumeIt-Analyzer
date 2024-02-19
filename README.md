# ResumeIt-Analyzer                
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)   

A Resume Analyzer using Natural Language Processing (NLP), Sumy library, Pyresparser, Pdfminer, and Streamlit is a tool designed to automatically parse and analyze resumes to extract relevant information. Here's a brief overview of each component:

1. Natural Language Processing (NLP): NLP is a field of artificial intelligence that focuses on the interaction between computers and humans through natural language. In this context, NLP techniques are used to process and understand the textual content of resumes.
2. Sumy library: Sumy is a Python library for extracting summary sentences from documents using various algorithms such as LexRank and LSA (Latent Semantic Analysis). It can be used to generate concise summaries of resume content.
3. Pyresparser: Pyresparser is a Python library specifically designed for parsing resumes (in various formats such as PDF, DOC, DOCX) and extracting structured information such as personal details, skills, education, work experience, etc.
4. Pdfminer: Pdfminer is a tool for extracting information from PDF documents. It is often used as a backend component in Python libraries for parsing PDF files, including Pyresparser, to extract text and layout information from PDF resumes.
5. Streamlit: Streamlit is a popular Python library for building interactive web applications for data science and machine learning projects. It allows developers to create user-friendly interfaces with minimal code, making it suitable for building a frontend interface for the resume analyzer tool.

![Alt text](C:\Users\Prathamesh Patil\OneDrive\Pictures\Screenshots)
   
## Source
- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/)
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).
- Dowmload sumy lib for summary extraction.

## Workflow
- The user uploads a resume file through the Streamlit interface.
- Pdfminer is used to extract text content from the uploaded PDF resume.
- Pyresparser parses the extracted text to identify and extract relevant information such as personal details, skills, work experience, etc.
- NLP techniques may be employed to further analyze the textual content, such as summarization of lengthy paragraphs or identifying key phrases.
- Sumy library could be utilized to generate a summary of the resume content.
- Finally, the analyzed information and summary are displayed back to the user via the Streamlit interface, providing insights into the resume's content in a user-friendly format.

## Features
- User's & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations
- Resume summary

## Usage
- `App.py` is the main Python file of Streamlit Web-Application. 
- `Courses.py` is the Python file that contains courses and youtube video links.
- Download XAMP or any other control panel, and turn on the Apache & SQL service.
- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.
