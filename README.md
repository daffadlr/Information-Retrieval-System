# Information-Retrieval-System
This project is an Information Retrieval (IR) system that processes text from PDFs and Word documents. It includes text preprocessing features such as tokenization, stemming, and stopword removal. The project is built using Python and provides a web-based interface using Streamlit.

Features
Extract text from PDF and Word (DOCX) files.
Preprocess text: Lowercasing, tokenization, stemming (Sastrawi), and stopword removal.
User Interface: Built with Streamlit for easy interaction.

Installation:
1. Make sure you have Python 3.8+ installed. Then, install the required dependencies:

pip install -r requirements.txt

2. If requirements.txt is missing, install the dependencies manually:

pip install PyPDF2 python-docx Sastrawi streamlit



How to Run:
1. Place your PDF and DOCX files inside the dokumen/ folder.
2. Run the Streamlit app with:

streamlit run bismillah.py

3.Open the local server link provided by Streamlit to interact with the application.

Project Structure

uasdatmin2/
│── bismillah.py           # Main script (Streamlit App)
│── dokumen/               # Folder for input documents (PDF, DOCX)
│── pdfgacor/              # Additional document storage
│── requirements.txt       # Dependencies (if available)

