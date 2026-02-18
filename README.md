# Text Analytics Spring 2026
**Student:** Shahzeb Ather
**University:** Loyola Marymount University
**Course:** Text Mining & Social Media Analytics
**Semester:** Spring 2026
**Instructor:** Ace Vo
## About This Repository
This repository contains my coursework for Text Analytics (Spring
2026).
Each assignment demonstrates different NLP techniques using Python.
## Assignments

### Assignment 1: Sentiment Analysis
- **Topic:** Comparing VADER and TextBlob sentiment analysis
- **Dataset:** [Dataset name]
- **Key Skills:** Text preprocessing, sentiment analysis, model
comparison
- **[View Assignment →](assignment1/)**

## Sentiment Analysis Project

## Project Overview
This project performs sentiment analysis on movie reviews using three different approaches: VADER, TextBlob, and a Transformer-based emotion classification model. The goal is to compare these models against manually labeled ground truth data to evaluate their strengths, weaknesses, and suitability for different types of text.

---

## Dataset Description
The dataset consists of movie reviews with associated sentiment labels. A random subset of 100 reviews was manually labeled as **positive**, **negative**, or **neutral** to serve as ground truth for evaluation.  
Key columns used in the analysis include:
- `review` / `clean_review`: Text of the movie review
- `sentiment`: Original dataset sentiment label
- `manual_label`: Manually assigned sentiment label (ground truth)

---

## Models Used
- **VADER**: A lexicon-based sentiment analyzer suitable for short and informal text.
- **TextBlob**: A lightweight sentiment analysis tool based on polarity scores.
- **Transformer (DistilBERT emotion model)**: A context-aware model that predicts emotions, which are mapped to sentiment labels.

---

## Key Findings Summary
- The **Transformer-based model** performed best on longer and more nuanced reviews due to its ability to capture context.
- **VADER** performed well on clearly polarized text but struggled with negation and sarcasm.
- **TextBlob** provided a reasonable baseline but showed weaker performance on complex or mixed-sentiment reviews.
- Manual labeling was critical for identifying true success and failure cases across models.

---

## How to Run Instructions
1. Open `Assignment_1_Sentiment_Analysis.ipynb`
2. Ensure required libraries are installed (`vaderSentiment`, `textblob`, `transformers`)
3. Run all cells from top to bottom
4. Ensure `manual_label_100.csv` is present in the same directory for evaluation steps

---

## Results Visualization
Model performance is evaluated using:
- Accuracy scores
- Confusion matrices
- Success and failure examples comparing model predictions to manual labels

Key results and example outputs are displayed directly in the notebook.

---

## Links to Files
- `Assignment_1_Sentiment_Analysis.ipynb` – Main analysis notebook
- `manual_label_100.csv` – Manually labeled ground truth dataset
- `AI_usage_log.md` – Documentation of AI assistance and identified AI errors
- `README.md` – Project documentation (this file)

---

## Conclusion
This project demonstrates how different sentiment analysis approaches perform on the same dataset and highlights the importance of ground truth labeling when evaluating model accuracy and behavior.

## Labeling Process

## Skills Demonstrated
- Python programming
- Natural Language Processing
- Data visualization
- Git version control
- Technical documentation
- AI-assisted development
  
## Tools & Libraries
- Python 3.9+
- Jupyter Notebooks
- pandas, numpy
- scikit-learn
- VADER, TextBlob
- matplotlib, seaborn
  
## Contact
- **Email:** sather@lion.lmu.edu
- **GitHub:** (https://github.com/shahzebather-ui)
- **LinkedIn:** www.linkedin.com/in/shahzebather
