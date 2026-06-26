# NLP Text Summarizer

A simple Natural Language Processing (NLP) project that generates a summary of a paragraph by selecting the most important sentences based on word frequency analysis.

## Objective

The objective of this project is to demonstrate a basic extractive text summarization technique using Python and Natural Language Processing concepts.

## Technologies Used

* Python
* Regular Expressions (re)
* Collections (Counter)

## How It Works

1. Accept a paragraph from the user.
2. Split the paragraph into sentences.
3. Calculate the frequency of each word.
4. Assign a score to every sentence based on word frequencies.
5. Select the highest-scoring sentences as the summary.
6. Display the generated summary.

## Run the Project

```bash
python main.py
```

## Sample Output

```text
Enter a paragraph:

Artificial Intelligence is transforming industries. Machine Learning is a branch of AI. AI is widely used in healthcare, education, and finance. Machine Learning enables computers to learn from data.

=== Summary ===

Machine Learning enables computers to learn from data.
Artificial Intelligence is transforming industries.
```

## Project Structure

```text
NLP-Text-Summarizer/
│
├── main.py
├── output.png
└── README.md
```

## Concepts Used

* Natural Language Processing (NLP)
* Extractive Text Summarization
* Word Frequency Analysis
* Sentence Scoring
* Regular Expressions
* Python Collections


## Future Improvements

* Implement TF-IDF based sentence scoring.
* Support PDF and text file summarization.
* Allow users to choose summary length.
* Add stop-word removal.
* Use transformer-based models such as BERT or T5.
* Develop a web interface for text summarization.


## Author

**Mahrukh**

Robotics & Intelligence Systems Student passionate about Artificial Intelligence, Machine Learning, Natural Language Processing, and intelligent software solutions.
