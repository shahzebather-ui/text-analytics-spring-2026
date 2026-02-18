# AI Usage Log

## Interaction 1: Data Cleaning & Preprocessing
**Task:** Clean review text for sentiment analysis  
**Prompt Used:** “How do I remove HTML tags and lowercase text in Python?”  
**AI Suggestion:** Use string operations and regular expressions to remove HTML tags and standardize casing.  
**What I Modified:** Adjusted the code to fit the existing DataFrame structure and column names.  
**Why Modified:** The dataset column names differed from the example provided.  
**What I Learned:** Text preprocessing must be aligned with the dataset schema.  
**AI Errors Found:** None.

---

## Interaction 2: Implementing VADER Sentiment Analysis
**Task:** Apply VADER sentiment analysis and generate predictions  
**Prompt Used:** “How do I apply VADER sentiment analysis to a pandas DataFrame?”  
**AI Suggestion:** Use `SentimentIntensityAnalyzer` and convert compound scores into binary sentiment labels.  
**What I Modified:** Adjusted threshold logic and column naming to align with assignment requirements.  
**Why Modified:** Needed consistent label format (positive/negative).  
**What I Learned:** Lexicon-based models rely heavily on surface-level polarity.  
**AI Errors Found:** None.

---

## Interaction 3: Implementing TextBlob Sentiment Analysis
**Task:** Generate TextBlob sentiment predictions and compare with manual labels  
**Prompt Used:** “How do I convert TextBlob polarity scores into sentiment labels?”  
**AI Suggestion:** Use polarity ≥ 0 as positive and < 0 as negative.  
**What I Modified:** Recomputed predictions directly on the manually labeled dataset to avoid merge issues.  
**Why Modified:** Merging caused column mismatches and errors.  
**What I Learned:** Simpler workflows reduce debugging risk.  
**AI Errors Found:** Initial suggestions assumed shared DataFrames, which caused KeyErrors.

---

## Interaction 4: Transformer-Based Emotion Model
**Task:** Apply a transformer model and map emotions to sentiment  
**Prompt Used:** “How do I use a transformer model for sentiment or emotion classification?”  
**AI Suggestion:** Use a DistilBERT emotion classifier and map emotions to sentiment categories.  
**What I Modified:** Limited input length and mapped only specific emotions (joy, love, surprise) to positive sentiment.  
**Why Modified:** Emotion labels do not directly equal sentiment polarity.  
**What I Learned:** Transformer models capture context better but require interpretation layers.  
**AI Errors Found:** None.

---

## Interaction 5: Evaluation & Comparison
**Task:** Compare model predictions with manual labels and extract success/failure examples  
**Prompt Used:** “How do I compare model predictions with ground truth labels?”  
**AI Suggestion:** Filter rows where predictions match or differ from manual labels.  
**What I Modified:** Ensured all comparisons used the manually labeled dataset as ground truth.  
**Why Modified:** Initial comparisons mistakenly used dataset sentiment instead of manual labels.  
**What I Learned:** Ground truth consistency is critical for valid evaluation.  
**AI Errors Found:** Early confusion between dataset sentiment and manual labels.

---

## Overall Reflection
AI assistance significantly accelerated development, debugging, and evaluation. Most issues encountered were due to dataset-specific constraints rather than incorrect AI guidance. Iterative clarification and simplification were key to successfully completing the assignment.
