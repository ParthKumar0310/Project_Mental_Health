#  Understanding Mental Health Conversations Across Cultures
### NLP & Network Analysis of Reddit and Beyond Blue

##  Project Overview

This project presents an end-to-end **Natural Language Processing (NLP)** pipeline for analysing mental health discussions across two online communities:

- 🇦🇺 **Beyond Blue** (Australia)
- 🌍 **Reddit** (Global)

The objective was to compare emotional expression, sentiment, behavioural patterns, and community interactions using modern NLP techniques, affective computing, and network analysis.

The project combines **sentiment analysis**, **emotion classification**, **valence-arousal modelling**, and **graph-based analysis** to understand how people discuss mental health across different online environments.

---

#  Dataset

The project combines publicly available mental health discussions collected from:

- **Beyond Blue** (Australian Mental Health Forum)
- **Reddit Mental Health Communities**

Approximately:

| Source | Records |
|---------|---------:|
| Reddit | 45,000+ |
| Beyond Blue | 18,000+ |
| **Total** | **60,000+ Posts & Comments** |

After preprocessing, approximately **158,000 text instances** were analysed.

---

#  Objectives

The project aimed to:

- Compare mental health discussions across Australian and global communities.
- Perform large-scale text preprocessing.
- Apply sentiment analysis techniques.
- Classify emotions using transformer-based models.
- Model emotional intensity using Valence-Arousal theory.
- Analyse emotional and lexical relationships using graph networks.
- Generate interpretable insights into online mental health discourse.

---

#  Technologies Used

### Programming

- Python

### NLP

- NLTK
- SpaCy
- Hugging Face Transformers
- RoBERTa GoEmotions

### Machine Learning

- Scikit-learn
- PyTorch

### Sentiment Analysis

- VADER
- TextBlob

### Data Processing

- Pandas
- NumPy

### Visualisation

- Matplotlib
- NetworkX

### Data Collection

- PRAW (Reddit API)
- BeautifulSoup

---

#  Project Pipeline

```
Data Collection
        │
        ▼
Text Cleaning & Preprocessing
        │
        ▼
Sentiment Analysis
(VADER + TextBlob)
        │
        ▼
Emotion Classification
(RoBERTa GoEmotions)
        │
        ▼
Valence-Arousal Modelling
(NRC VAD)
        │
        ▼
Network Analysis
        │
        ▼
Cross-Platform Comparison
        │
        ▼
Business & Research Insights
```

---

#  Features

###  Data Collection

- Reddit API (PRAW)
- BeautifulSoup Web Scraping
- Metadata extraction
- Thread hierarchy collection

###  Text Preprocessing

- Lowercasing
- Tokenisation
- Lemmatization
- Stop-word removal
- HTML removal
- URL removal
- Emoji removal
- Duplicate removal

###  Sentiment Analysis

- VADER
- TextBlob

Generated:

- Positive
- Neutral
- Negative sentiment

---

###  Emotion Classification

Implemented using

**RoBERTa GoEmotions**

Mapped 28 emotions into Ekman's emotional categories:

- Joy
- Sadness
- Fear
- Anger
- Disgust
- Surprise
- Neutral

---

###  Valence-Arousal Analysis

Used the **NRC-VAD Lexicon** to analyse:

- Emotional intensity
- Emotional activation
- Emotional polarity

---

###  Network Analysis

Constructed multiple graph networks including:

- Emotion Co-occurrence Networks
- Lexical Networks
- Bipartite Emotion-Word Networks
- PMI Semantic Networks

using **NetworkX**.

---

#  Key Findings

- Analysed more than **60,000 mental health discussions** from Australian and global communities.
- Beyond Blue discussions contained substantially more neutral and support-oriented language.
- Reddit discussions showed greater emotional diversity and higher emotional intensity.
- Fear and sadness dominated crisis-related communities.
- Network analysis revealed stronger lexical clustering in Beyond Blue and more fragmented discussions on Reddit.

---

#  Project Structure

```
Mental-Health-NLP/
│
├── Data/
├── Notebooks/
├── Models/
├── Figures/
├── Outputs/
├── Report.pdf
├── requirements.txt
└── README.md
```

---

#  Skills Demonstrated

- Natural Language Processing (NLP)
- Machine Learning
- Text Analytics
- Sentiment Analysis
- Emotion Classification
- Feature Engineering
- Data Preprocessing
- Exploratory Data Analysis
- Network Analysis
- Graph Analytics
- Python Programming
- Research & Statistical Analysis

---

# Future Improvements

- Fine-tune transformer models for mental health classification.
- Deploy an interactive dashboard for real-time analysis.
- Build an LLM-powered chatbot for summarising mental health discussions.
- Apply Graph Neural Networks (GNNs) for community detection.
- Extend the analysis to multilingual datasets.

---

#  Author

**Parth Kumar**

Master of Data Science  
The University of Adelaide

LinkedIn: [*(Parth Kumar)*](https://www.linkedin.com/in/parth-kumar-2032071a0/)

---
