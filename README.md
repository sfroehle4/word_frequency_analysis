# Word Frequency in Peter Pan by J.M. Barrie

## Introduction

In this Jupyter Notebook, we analyze the word frequency in the novel "Peter Pan" by J.M. Barrie. The project involves web scraping the text from Project Gutenberg, processing it, and identifying the most common words.

This project is inspired by DataCamp.

## Table of Contents

1. [Common Imports](#common-imports)
2. [Import HTML file and extract the text](#import-html-file-and-extract-the-text)
3. [Preparing Data](#preparing-data)
4. [Removing Stopwords](#removing-stopwords)
5. [Get The Answer](#get-the-answer)

## Common Imports

For this project, we used the following Python packages:

- `requests`: For making HTTP requests
- `BeautifulSoup` from `bs4`: For parsing HTML and XML documents
- `nltk`: Natural Language Toolkit for processing human language
- `Counter` from `collections`: For counting occurrences of words

```python
import requests
from bs4 import BeautifulSoup
import nltk
from collections import Counter
```

## Reproducing the Analysis

To reproduce the analysis, follow these steps:

1. **Install Dependencies:**
    Run the following commands in your terminal or command prompt:

    ```bash
    pip install requests
    pip install beautifulsoup4
    pip install nltk
    ```

2. **Open and Run Jupyter Notebook:**
   - Open the Jupyter Notebook (`your_notebook.ipynb`) in your preferred environment.
   - Run the notebook cells in order by executing them.

## Conclusion

This Jupyter Notebook provides insights into the word frequency in "Peter Pan" and can be adapted for similar analyses.

Feel free to reach out if you have any questions or suggestions!
```
