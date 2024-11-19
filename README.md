#  Text Summarization using nlp
# project overview
This repository demonstrates implementation of a text summarization system that efficiently condenses large text documents into concise summaries. 
It supports both extractive summarization (selecting key sentences from the text) and abstractive summarization (generating summaries in human-like language).
This project  presents a Python-based approach to both abstractive and extractive summarization. Extractive methods select key sentences from the source, while abstractive methods generate new, rephrased content.

# setup 
1.Install Dependencies
  Make sure Python 3.8+ is installed, then create a virtual environment (optional) and install the dependencies:
  
     pip install -r requirements.txt
     
2.Package installation

     pip install PyPDF2
     pipinstall urllib
     pip install transformers

 # Implementation details
1. Data Input-User 

   selects input mode:
   Manual text entry,Upload text/PDF file,Extract text from a URL
   
2.Preprocessing
   Text cleaning:
     Remove non-alphanumeric characters.
     Lemmatization and stop-word removal.
   Tokenization:
     Split text into sentences for extractive methods.
     Processed chunks for abstractive methods.
3.Summarization
   Extractive Approach: Utilizes TF-IDF to highlight critical sentences.
   Abstractive Approach: Employs transformer models for concise paraphrasing.

# output
  Summarized passage 
  Total number of words in original passage
  Total number of words in summarized passage
