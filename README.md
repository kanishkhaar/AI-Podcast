# 🎙️ AI Podcast Transcription & Topic Segmentation System  
## AI-Powered Audio Intelligence and Content Structuring Platform  

The AI Podcast Transcription & Topic Segmentation System is an end-to-end AI application that converts podcast audio into structured transcripts and automatically segments the content into meaningful topic sections.

The system integrates Speech-to-Text models with Natural Language Processing techniques to create an intelligent audio analysis pipeline. It enables efficient content indexing, structuring, and analysis of long-form audio content.


## 🚀 Features

- Automatic podcast transcription  
- High-accuracy transcription using OpenAI Whisper  
- Topic segmentation using TextTiling algorithm  
- End-to-end automated processing pipeline  
- Speech-to-Text benchmarking module  
- Interactive web interface using Streamlit  
- Cloud deployment support  


## 🗂️ Modules Used

### Speech-to-Text Module
Handles audio-to-text conversion using:
- OpenAI Whisper
- Vosk (optional benchmarking)

### Text Processing Module
Includes:
- Text cleaning and normalization
- Sentence tokenization
- Stopword removal

### Topic Segmentation Module
Implements:
- TextTiling Algorithm
- Topic boundary detection
- Segmented transcript generation

### Web Application Module
- Streamlit-based interactive UI
- Audio file upload
- Transcript display
- Topic-wise output visualization


## 🧠 Machine Learning & NLP Components

- OpenAI Whisper – Speech Recognition  
- TextTiling Algorithm – Topic Segmentation  
- NLTK – Natural Language Processing  
- PyTorch – Deep learning backend  

Evaluation:
- Transcription benchmarking  
- Comparative STT performance analysis  


## 🧠 Processing Logic

1. User uploads podcast audio (.mp3/.wav).  
2. Speech-to-Text engine converts audio into transcript.  
3. Transcript is cleaned and preprocessed.  
4. TextTiling algorithm detects topic boundaries.  
5. Transcript is divided into structured topic segments.  
6. Segmented results are displayed in the web interface.  


## 🖥️ Web Interface

- Upload podcast audio file  
- Generate transcript  
- View topic-segmented output  
- Analyze structured transcript  
- Download processed results  


## ⚙️ Tech Stack

Backend: Python  
Frontend & Deployment: Streamlit  
Speech Recognition: OpenAI Whisper, Vosk  
NLP Processing: NLTK  
Deep Learning: PyTorch  
Audio Processing: FFmpeg  



## 📁 How to Run the Project Locally

1. Clone the repository  
   git clone https://github.com/ruturajmundhe/Automated-Podcast-Transcription-and-Topic-Segmentation-Audio-Analysis-Project.git  

2. Navigate to project directory  
   cd Automated-Podcast-Transcription-and-Topic-Segmentation-Audio-Analysis-Project  

3. Install dependencies  
   pip install -r requirements.txt  

4. Run the Streamlit application  
   streamlit run app.py  

5. Open the generated local URL in your browser  


## 🌍 Objective

To build an AI-powered system that transforms unstructured audio content into structured, searchable, and analyzable text for content intelligence applications.


## 🔮 Future Enhancements

- Automatic summarization per topic  
- Speaker diarization  
- Real-time transcription  
- Cloud storage integration  
- REST API development  
- Transcript search functionality  


## 👨‍💻 Developed Under

AI & Machine Learning Internship Project  
Podcast Audio Intelligence System  
