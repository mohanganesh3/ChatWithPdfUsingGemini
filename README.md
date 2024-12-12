# ChatWithPdfUsingGemini

ChatWithPdfUsingGemini is an AI-powered chatbot system built to interact with PDF documents. Using Gemini, the system can read and understand the content of a PDF and answer questions based on it, making it a powerful tool for document-based queries. This project aims to leverage advanced NLP techniques to provide insightful, context-aware responses from a variety of PDFs.

# Features
	•	PDF Parsing: Efficiently extract and parse text from PDF files.
	•	AI-powered Chatbot: Engage in a conversation with the PDF content.
	•	Contextual Understanding: Understand the context of the PDF to answer specific queries.
	•	Interactive UI: User-friendly interface for uploading PDFs and interacting with the chatbot.

# Technologies Used
	•	Gemini: To process and understand the content of the PDFs.
	•	Python: For building the backend.
	•	Streamlit: For creating an interactive web interface.
	•	OpenAI’s GPT: To power the AI model that understands the content and generates responses.

# Installation

# Prerequisites
	•	Python 3.7 or later
	•	pip (Python package installer)

# Step-by-Step Installation Guide
	1.	Clone the Repository:
  Clone the repository to your local machine:
  git clone https://github.com/mohanganesh3/ChatWithPdfUsingGemini.git
  cd ChatWithPdfUsingGemini
  2.	Set Up a Virtual Environment:
  It’s recommended to use a virtual environment to manage dependencies:
  python3 -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
  3.	Install Required Dependencies:
  Install the required Python libraries using pip:
  pip install -r requirements.txt
  4.	Set Up Environment Variables:
  Make sure to set up any necessary API keys or configuration settings for the Gemini and OpenAI models. These can typically be added to a .env file:
  GEMINI_API_KEY=<your_gemini_api_key>
  5.	Run the Application:
  Start the application using Streamlit:
  streamlit run app.py
  The app will open in your default browser. You can upload a PDF and start chatting with the chatbot
  
  # Usage
	1.	Upload PDF:
	•	After launching the app, click the “Upload” button to select and upload a PDF file.
	2.	Ask Questions:
	•	Once the PDF is loaded, enter your questions related to the content of the PDF.
	•	The chatbot will analyze the text and provide you with relevant answers.
	3.	Interactive Chat:
	•	You can continue chatting with the chatbot by asking more questions. The AI will keep responding based on the PDF content.

 # How It Works

 The system uses the following steps to provide answers:
	1.	PDF Extraction: The system reads the PDF file and extracts its text.
	2.	Content Processing: The extracted content is processed and split into manageable chunks for better comprehension.
	3.	Question Answering: The Gemini model generates answers based on the context of the PDF.
	4.	User Interaction: The user interacts with the system by typing queries, and the AI generates relevant responses.

 # Example

  Sample Interaction:
	1.	Upload PDF: A research paper or documentation.
	2.	Ask: “What is the main objective of this study?”
	3.	Response: “The main objective of this study is to investigate the impact of AI on healthcare systems…”
