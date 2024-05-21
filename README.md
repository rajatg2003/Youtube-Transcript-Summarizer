# Youtube-Transcript-Summarizer
In this project, you will be creating a Chrome Extension that will apply to the backend REST API where it will do NLP and respond with a summary of YouTube text.
The steps involved in building of this project include :- 
1) Download YouTube video's Audio
2) English ASR with HuggingSound
3) Audio chunking
4) Audio Transcription/ASR /Speech to text
5) Text Summarization


The project link for the Youtube Transcript Summarizer :- https://colab.research.google.com/drive/1eDTLKwXPF3ZEMIrGANinQeXOISrJC9gO?usp=sharing#scrollTo=rntJPk4H2OoF


High-Level Approach
1) Find the text / subtitle of YouTube Video Id that you use using the Python API.
2) Make text summaries of text found using HuggingFace transformers.
3) Create a Flask backend REST API to display client summarization service.
4) Upgrade the chrome extension that will use the backend API to display user text.
