## Scientific Text Summarizer

A compact NLP-based tool to extract keywords and summarize scientific abstracts using classical techniques like TF-IDF and LSA.

## Features:
- Sentence tokenization and stopword removal using NLTK
- Keyword extraction via TF-IDF
- Summarization using:
  - TF-IDF scoring to select the most important sentence
  - LSA (Latent Semantic Analysis) using the Sumy library

## Tech Stack:
- Python
- NLTK
- Scikit-learn
- Sumy

## Sample Input:
"Artificial Intelligence (AI) is transforming scientific research. With capabilities in automating data analysis, AI systems can process enormous datasets, generate hypotheses, and even assist in experimental design. Natural Language Processing (NLP) specifically aids in mining scientific literature by summarizing key findings, extracting concepts, and linking related works. Tools like TF-IDF, sentence embeddings, and deep learning summarizers are gaining popularity in research institutions."

## Sample Output (TF-IDF Summary):
"Artificial Intelligence (AI) is transforming scientific research."

## Sample Output (LSA Summary):
- Artificial Intelligence (AI) is transforming scientific research.
- Natural Language Processing (NLP) specifically aids in mining scientific literature by summarizing key findings, extracting concepts, and linking related works.

## How to Run:
1. Open the notebook in Google Colab.
2. Run the following to install dependencies:
   !pip install nltk sumy
3. Execute all notebook cells sequentially.

## Future scope: 
Add transformer-based summarizers like BART or T5.

## Author:
Aarohi Jain
B.Tech Student - Robotics & AI
Manav Rachna University
Email: aarohi.jain.2007@gmail.com
