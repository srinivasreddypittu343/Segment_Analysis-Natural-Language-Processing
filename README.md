# Srinivas Reddy Pittu (700777009)
# Segment_Analysis-Natural-Language-Processing
This contains NLP assignment solutions featuring text preprocessing, lemmatization, POS tagging, Named Entity Recognition, and pronoun ambiguity detection using Python and spaCy, along with written explanations of key NLP and clustering concepts.
# 🚀 NLP Coding Tasks – Part C

## 🧩 Task Overview

### 🔹 **Q1 – Text Preprocessing Pipeline**
Implements:
- Tokenization  
- Stopword Removal  
- Lemmatization (using spaCy)  
- POS Filtering (keeps only *NOUN* and *VERB*)  

📌 *Goal:* Build a compact, meaningful representation of text by retaining only the most informative linguistic units.

---

### 🔹 **Q2 – Named Entity Recognition + Pronoun Ambiguity Check**
Implements:
- Named Entity Recognition (NER)  
- Detection of pronouns such as *he*, *she*, *they*  
- Alert for potential **pronoun ambiguity**  

📌 *Goal:* Identify entities in text and warn when ambiguous references may lead to misinterpretation.

---

## ⚙️ How to Run

Install spaCy and the English model:

```bash
pip install spacy
python -m spacy download en_core_web_sm
