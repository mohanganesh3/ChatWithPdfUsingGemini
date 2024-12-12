#  ChatWithPdfUsingGemini  
**ChatWithPdfUsingGemini** is your AI-powered companion for understanding and interacting with PDF documents. Forget endless scrolling and searching through text—just ask questions, and let the chatbot do the heavy lifting! Built with the powerful **Gemini** API, this app transforms static PDFs into dynamic, interactive conversations.  

## 🌟 Features  
- **📄 PDF Parsing**: Efficiently extract text from your PDFs.  
- **🤖 AI Chatbot**: Engage in natural conversations based on PDF content.  
- **🧠 Contextual Insights**: Ask specific questions and get accurate answers.  
- **💻 Interactive UI**: Easy-to-use interface for uploading PDFs and interacting with the chatbot.  

## 🛠️ Technologies Used  
- **Gemini**: For intelligent PDF content analysis.  
- **Python**: The backbone of the system.  
- **Streamlit**: For a clean, interactive web interface.  

## 📥 Installation Guide  
Make sure you have **Python 3.7+** and **pip** installed.  

### Step 1: Clone the Repository  
Clone the repository to your local machine:  
`git clone https://github.com/mohanganesh3/ChatWithPdfUsingGemini.git`  
`cd ChatWithPdfUsingGemini`  

### Step 2: Set Up a Virtual Environment  
It’s recommended to use a virtual environment to manage dependencies:  
`python3 -m venv venv`  
`source venv/bin/activate`  # On Windows, use `venv\Scripts\activate`  

### Step 3: Install Required Dependencies  
Install the necessary Python libraries by running:  
`pip install -r requirements.txt`  

### Step 4: Set Up Environment Variables  
Make sure to set up the required API keys for **Gemini**. You can add them to a `.env` file in the root of your project:  
`GEMINI_API_KEY=<your_gemini_api_key>`  

### Step 5: Run the Application  
Start the application using **Streamlit**:  
`streamlit run app.py`  
This will open the app in your default browser. You can upload a PDF and start interacting with the chatbot.  

## 💡 Usage  
1. **Upload PDF**: Select and upload a PDF file in the app.  
2. **Ask Questions**: Type questions about the content, and the AI will provide you with precise answers based on the document.  
3. **Interactive Chat**: Continue asking more questions, and the chatbot will respond based on the content of the PDF.  

## ⚙️ How It Works  
1. **PDF Extraction**: The system reads the PDF file and extracts its text.  
2. **Content Processing**: The extracted content is split into manageable chunks for better comprehension.  
3. **Question Answering**: The Gemini model generates answers based on the context of the PDF.  
4. **User Interaction**: Users type queries, and the AI generates responses relevant to the content of the PDF.  

## 📝 Example  
### Sample Interaction:
1. **Upload PDF**: Upload a research paper or any document.  
2. **Ask**: “What is the main objective of this study?”  
3. **Response**: “The main objective of this study is to investigate the impact of AI on healthcare systems…”  
