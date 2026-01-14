# Grammar Evaluation System
Whisper + NLP + LLM Grammar Scoring

Overview  
This project implements an end-to-end spoken English grammar evaluation pipeline.  
It converts raw speech audio into text using OpenAI Whisper, cleans conversational noise, performs sentence-level linguistic analysis, and assigns grammar quality scores using both LLM-based and rule-based methods.

The system is designed as a research-focused ML pipeline and does not rely on any frontend or backend components.

---

Tech Stack  

Python  

OpenAI Whisper (Speech-to-Text)  

Librosa (Audio Processing)  

NLTK (Sentence & Token Analysis)  

OpenAI GPT (Grammar Scoring)  

LanguageTool API (Rule-based Grammar Checking)  

Google Colab (GPU Supported)

---

Pipeline  

Audio (.wav)  
→ Whisper Transcription  
→ Noise & Filler Cleaning  
→ Sentence Segmentation  
→ Token Analysis  
→ Grammar Scoring (1–5)

---

Dataset  

Source: Kaggle – SHL Intern Hiring Assessment  

Data Type: Spoken English interview audio  

Used for transcription, linguistic analysis, and grammar evaluation.

---

Grammar Scoring Criteria  

1 – Poor grammar, broken structure  

2 – Frequent grammatical mistakes  

3 – Fair grammar with noticeable errors  

4 – Good grammar with minor mistakes  

5 – Excellent grammar with minimal or no errors  

---

Sample Output  

Original Sentence:  
She don't like the movie.

Grammar Score:  
2 / 5

Issues Detected:  
Subject–verb agreement error

---

Key Features  

Speech-to-text transcription using Whisper  

Audio visualization (waveform & spectrogram)  

Conversational filler removal (um, uh, like, etc.)  

Sentence-level token statistics  

LLM-based grammar evaluation  

Rule-based grammar validation  

CSV export of transcriptions  

---

Use Case  

Automated spoken English assessment  

Interview speech evaluation  

Language learning applications  

Grammar analysis research  

---

Description  

Built an end-to-end spoken grammar evaluation system using OpenAI Whisper and NLP techniques. Processed raw interview audio, cleaned conversational artifacts, analyzed sentence structure, and evaluated grammar quality using LLM-based and rule-based scoring methods.

---

License  

MIT License  

Free to use, modify, and distribute with attribution.

---

Author  

Aman Kumar  
Omshubra singha 
