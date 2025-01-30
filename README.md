# MatchBOOK: A Semantic Book Recommender

## Project Overview

MatchBOOK is a semantic book recommendation system designed to suggest books based on user preferences and emotional tones. Leveraging state-of-the-art Natural Language Processing (NLP) techniques and tools such as OpenAI's GPT models, LangChain, and Gradio, this project provides users with personalized book recommendations.

## Features

- **Exploratory Data Analysis (EDA):** Analyze the dataset for insights and trends.
- **Sentiment Analysis:** Determine emotional tones of book descriptions to align recommendations with user preferences.
- **Semantic Search:** Use vector-based search for finding books most similar to user inputs.
- **Dashboard:** Interactive Gradio-powered interface for an enhanced user experience.

## Repository Structure

```
MatchBOOK/
├── .idea/                      # Project settings (IDE-specific)
├── EDA.ipynb                   # Notebook for Exploratory Data Analysis
├── README.md                   # Project documentation
├── books_cleaned.csv           # Cleaned dataset of books
├── books_with_categories.csv   # Dataset with categorized books
├── books_with_emotions.csv     # Dataset with emotion-labeled books
├── cover-not-found.jpg         # Placeholder image for missing covers
├── dashboard.py                # Code for Gradio-based dashboard
├── sentiment-analysis.ipynb    # Notebook for sentiment analysis tasks
├── tagged_desc.txt             # Preprocessed book descriptions
├── text-classifications.ipynb  # Notebook for text classification
├── vector_search.ipynb         # Notebook for semantic search implementation
```

## Tools and Technologies

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **NLP Tools:** OpenAI's GPT, LangChain
- **Frontend:** Gradio for building the interactive user interface
- **Data Visualization:** Seaborn and Matplotlib for visual exploration

## Dataset

The dataset used in this project contains book metadata, including descriptions, categories, and emotion labels. Datasets such as `books_cleaned.csv`, `books_with_categories.csv`, and `books_with_emotions.csv` are preprocessed versions used throughout the project.

## Key Notebooks and Scripts

### 1. EDA.ipynb
Performs exploratory data analysis to uncover trends in the dataset.

### 2. sentiment-analysis.ipynb
Analyzes the sentiment and emotional tones of book descriptions.

### 3. text-classifications.ipynb
Classifies books into categories based on their descriptions.

### 4. vector_search.ipynb
Implements semantic search using vector embeddings.

### 5. dashboard.py
A Gradio-based web application allowing users to interact with the book recommendation system.

## How to Run the Project

### Prerequisites

- Python 3.8+
- Install dependencies using the following command:
  ```bash
  pip install -r requirements.txt
  ```

### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MatchBOOK.git
   ```

2. Navigate to the project directory:
   ```bash
   cd MatchBOOK
   ```

3. Run the dashboard:
   ```bash
   python dashboard.py
   ```

4. Access the application on your local browser (default: `http://127.0.0.1:7860`).


