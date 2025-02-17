# Left vs Right: Analysis of the Media Coverage of the 2024 U.S. Elections

## Overview

This project aims to analyze the media coverage of the 2024 U.S. presidential elections using Natural Language Processing (NLP) techniques. The analysis focuses on articles from newspapers classified as left-leaning, right-leaning, and centrist by AllSides.com. A total of 1200 articles were analyzed, with 434 from left-leaning sources, 428 from right-leaning sources, and 382 from centrist sources. All articles were published between September 1, 2024, and January 1, 2025, and cover topics related to the presidential elections.

## Key Findings

- **Major Themes:** Five major themes emerged: elections, domestic policy, foreign policy, economy, and justice.
- **Candidate Popularity:** Donald Trump was mentioned significantly more than Biden or Harris, with approximately 900 appearances compared to 400 for Harris and only 200 for Biden.
- **Titles:** Right-leaning media referred to Trump as "President" or "Former President" more often (120 times) than left-leaning media (80 times).
- **Voting Rights:** The transition to voting without "Voter ID" was mentioned more by left-leaning media (5 times) than right-leaning media (1 time).
- **Economy and Domestic Policy:** Right-leaning media discussed these topics with more negativity than left-leaning media, possibly due to the Democrats being in power during the period of the articles.

## Methodologies Used

- **Word Frequency Analysis:** To identify the most commonly used words and phrases in the articles.
- **N-gram Analysis:** To examine the frequency of contiguous sequences of n items from a given sample of text.
- **Topic Modeling with LDA:** To uncover the abstract "topics" that occur in the collection of articles.
- **Sentiment Analysis:** Using both rule-based and context-based deep learning models to determine the sentiment of the articles.

## Project Structure

- `notebook.ipynb`: Jupyter notebook containing the entire analysis, including data preprocessing, analysis, and visualization.
- `lda_model/`: files containing the LDA model for topic modeling

## Limitations
- Sample Size: Only 1200 articles were analyzed.
- Single Source: The left/right segmentation relies solely on AllSides.
- Source Diversity: Articles are from newspapers with varying levels of objectivity. Including diverse sources like TV talk shows, radio transcripts, and
tweets could provide more insights.
- Resource Constraints: The analysis was conducted over a weekend with limited computational resources.

## Future Work
Expand Analysis: Conduct a similar analysis on a larger scale for the French media leading up to the 2027 presidential elections.
Diverse Sources: Include a wider variety of media sources to capture more nuanced insights.

## Contact
For any questions or collaborations, feel free to reach out to me on LinkedIn or open an issue in this repository.

