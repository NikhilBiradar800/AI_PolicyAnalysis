# AI Policy Analysis Project

## Overview

This project focuses on analyzing the recent positions of leading countries in the realm of Artificial Intelligence (AI), specifically China, Europe, and the United States. The analysis involves extracting insights from provided documents, categorized into "Main sources" and "Additional sources."

While these documents may not fully represent the countries' policies and strategies, due to time constraints, students are advised to prioritize the provided materials.

## Analysis Process

### 1. Document Categorization

- `Main_sources/`: Folder containing primary documents for mandatory analysis.
- `Additional_sources/`: Folder for optional documents, including "AI_EUvsUS.pdf."

### 2. PDF Text Extraction

- Utilize Python to programmatically extract text from PDF documents for analysis.

### 3. Text Analysis

#### Text Cleaning and Tokenization

- Load resume data from the provided `resumes.csv` file.
- Clean the text by converting to lowercase, removing stopwords, and ensuring alphanumeric content.

#### N-grams and Topic Detection

- Generate bi-grams and tri-grams to capture meaningful phrases in the text.
- Utilize Latent Dirichlet Allocation (LDA) for topic detection in the resume data.

#### Word Cloud Generation

- Create word clouds to visually represent the most frequent words in the text.

#### Statistics Calculation

- Calculate various statistics, including the number of words, unique words, and entropy of the text.

#### Network Generation

- Create a network graph to visualize relationships between words in the resume text.

### 4. Report Generation

- For each resume:
  - Generate bi-grams and tri-grams.
  - Perform topic detection and generate word clouds.
  - Calculate statistics and visualize networks.
  - Write findings in the report file.

### 5. Top Words and Bigrams Analysis

- Calculate and print top words and bigrams for China, Europe, and the US.
- Load and preprocess text data for EU and US.

### 6. Generate Word Clouds

- Generate word clouds for China, Europe, and the US.

## How to Run the Code

1. Ensure Python is installed on your machine.
2. Install required packages by running:
   ```bash
   pip install -r requirements.txt

