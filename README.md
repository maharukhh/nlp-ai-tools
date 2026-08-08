# NLP & AI Tools
A collection of Natural Language Processing (NLP) and AI-powered language projects developed using Python. This repository showcases practical applications of text processing, language understanding, summarization, and intelligent language-based solutions.
## About This Repository
This repository contains projects focused on Natural Language Processing and AI language applications. Each project explores different NLP techniques and demonstrates how intelligent systems can process, analyze, and generate human language.
New NLP projects will be added as I continue learning and exploring modern AI technologies.
## Projects Included (Current)
### 1. NLP Text Summarizer
Automatically generates concise summaries from lengthy text using Natural Language Processing techniques.
* Concepts: Text summarization, sentence scoring, extractive summarization
### 2. AI Autocorrect Tool
A Python-based application that detects and corrects spelling mistakes in text.
* Concepts: Edit distance, spell checking, text correction
### 3. AI Interview Question Generator
Generates interview questions based on different topics and job roles.
* Concepts: Template-based generation, topic modeling
### 4. AI-Based Language Learning App
An interactive application designed to help users practice and improve language skills.
* Concepts: Vocabulary practice, interactive quizzing, language learning
### 5. Sentiment Analysis Tool
A lexicon-based sentiment analyzer that classifies text as Positive, Negative, or Neutral, with negation handling (e.g. "not happy" correctly flips to negative).
* Algorithm: Lexicon-based scoring with negation detection
* Concepts: Sentiment classification, text tokenization, polarity scoring
### 6. AI Chatbot
A rule-based, pattern-matching chatbot in the style of the classic ELIZA program, using regex rules to detect intent and hold a light conversation.
* Algorithm: Pattern matching (regex rules) with conversational memory
* Concepts: Dialogue systems, intent detection, rule-based NLP
### 7. Text Classification Tool
Classifies short text snippets into categories (Sports, Technology, Politics, Entertainment) using a Naive Bayes classifier.
* Algorithm: TF-IDF + Multinomial Naive Bayes
* Concepts: Supervised text classification, feature vectorization
### 8. Machine Translation Tool
A word-for-word English ↔ Urdu translator using a built-in dictionary lookup, demonstrating the core idea behind lookup-based translation.
* Algorithm: Dictionary-based word substitution
* Concepts: Bilingual lookup translation, tokenization
### 9. Named Entity Recognition (NER) Extractor
Extracts likely dates, organizations, locations, and person/place names from text using regex patterns and capitalization heuristics.
* Algorithm: Rule-based pattern matching and heuristic classification
* Concepts: Entity extraction, regex-based information extraction
### 10. Speech Processing Tool
A two-way speech tool: converts typed text to spoken audio (Text-to-Speech) and transcribes spoken audio from a microphone into text (Speech-to-Text).
* Algorithm: Offline TTS engine + cloud-based speech recognition
* Concepts: Speech synthesis, speech-to-text transcription
### 11. Question Answering System
Given a passage and a question, finds the most relevant sentence containing the answer using TF-IDF similarity.
* Algorithm: TF-IDF + cosine similarity (extractive QA)
* Concepts: Information retrieval, sentence-level relevance ranking
### 12. LLM Applications Toolkit
A wrapper around a Large Language Model API offering ready-made modes: text summarization, tone rewriting, and free-form question answering.
* Concepts: Prompt engineering, LLM API integration
### 13. Keyword/Topic Extractor
Extracts the most important keywords from a document using TF-IDF scoring against a background corpus.
* Algorithm: TF-IDF keyword scoring
* Concepts: Keyword extraction, corpus-relative term weighting
### 14. Fake News / Misinformation Detector (Educational Demo)
Classifies news headlines as "Likely Real" or "Likely Fake" using a Naive Bayes classifier trained on a small labeled toy dataset.
* Algorithm: TF-IDF + Multinomial Naive Bayes
* Concepts: Text classification, misinformation pattern recognition
### 15. Resume Parser & Analyzer
Extracts structured information (email, phone, years of experience, skills) from raw resume text using regex and keyword matching.
* Algorithm: Regex pattern matching + keyword lookup
* Concepts: Information extraction, structured data parsing
### 16. Plagiarism / Text Similarity Checker
Compares two texts and reports a similarity score using TF-IDF vectors and cosine similarity.
* Algorithm: TF-IDF + cosine similarity
* Concepts: Text similarity, duplicate/paraphrase detection
### 17. AI Story/Poem Generator
Generates original, semi-coherent short text by learning word-transition probabilities from a source text using a Markov chain.
* Algorithm: Markov chain text generation
* Concepts: Probabilistic language modeling, generative text
### 18. Text-Based Emotion Detector
Detects fine-grained emotions (Joy, Anger, Sadness, Fear, Surprise) in text using built-in emotion word lexicons.
* Algorithm: Multi-class lexicon-based scoring
* Concepts: Emotion classification, multi-label text analysis
## Technologies Used
* Python
* NLTK
* Scikit-learn
* Pandas
* NumPy
* Regular Expressions (Regex)
* pyttsx3 / SpeechRecognition
* Anthropic API
* Git & GitHub
## Installation
Clone the repository:
```bash id="c1m8ra"
git clone https://github.com/maharukhh/nlp-ai-tools.git
cd nlp-ai-tools
```
Install the required packages:
```bash id="n9k2sd"
pip install -r requirements.txt
```
## Running a Project
Navigate to the desired project folder and run the Python file.
```bash id="p4x8lm"
cd "project-folder"
python main.py
```
Project-specific instructions (including any extra installs) can be found inside each project's own README.
## Project Structure
```text id="q8m1zn"
nlp-ai-tools/
│
├── NLP Text Summarizer/
├── AI Autocorrect Tool/
├── Interview Question Generator/
├── AI-Based Language Learning App/
├── Sentiment Analysis Tool/
├── AI Chatbot/
├── Text Classification Tool/
├── Machine Translation Tool/
├── Named Entity Recognition (NER) Extractor/
├── Speech Processing Tool/
├── Question Answering System/
├── LLM Applications Toolkit/
├── Keyword-Topic Extractor/
├── Fake News Detector/
├── Resume Parser & Analyzer/
├── Plagiarism Checker/
├── AI Story-Poem Generator/
├── Emotion Detector/
├── requirements.txt
└── README.md
```
Each project typically includes:
* Source Code
* Datasets (if applicable)
* Output Screenshots
* Individual README Files
## Topics Covered
* Natural Language Processing (NLP)
* Text Processing
* Text Summarization
* Spell Checking
* Language Learning
* Sentiment & Emotion Analysis
* Conversational AI / Chatbots
* Text Classification
* Machine Translation
* Named Entity Recognition (NER)
* Speech Processing
* Question Answering Systems
* Large Language Model (LLM) Applications
* Text Similarity & Plagiarism Detection
* Generative Text (Markov Chains)
* Python Programming
## Learning Outcomes
This repository helps in understanding:
* How NLP systems process and analyze human language
* How classic ML techniques (TF-IDF, Naive Bayes) apply to text
* How rule-based and lexicon-based NLP methods work without heavy models
* How to integrate real LLM APIs into practical applications
* Building interactive, offline-friendly Python NLP tools
## Future Projects
This repository will continue to grow with projects related to:
* Advanced Chatbots (LLM-powered, multi-turn memory)
* Transformer-based Text Classification
* Neural Machine Translation
* Transformer-based NER (spaCy/Hugging Face pipelines)
* Speech Emotion Recognition
* Document-level Question Answering (RAG)
## Author
**Mahrukh**

Robotics & Intelligence Systems Student passionate about Artificial Intelligence, Machine Learning, Natural Language Processing, and intelligent software solutions.

---
⭐ Feel free to explore the projects and follow my journey in Artificial Intelligence and Natural Language Processing.

