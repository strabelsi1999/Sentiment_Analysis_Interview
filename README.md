# Project Overview
This project focuses on analyzing public sentiment regarding Andrew Tate based on comments from his interview with Piers Morgan on YouTube. The objective is to determine whether the general perception leans positively or negatively and to understand the structure of online discussions using sentiment analysis and network analysis.

# Problem Description
Public opinion on controversial figures is often shaped by algorithmic content curation, which reinforces users' existing biases. This project aims to quantify and visualize the sentiment expressed in thousands of YouTube comments, providing a more objective representation of audience reactions.

# The study leverages two analytical approaches:
Sentiment Analysis – Using Natural Language Processing (NLP) techniques such as VADER and NRC Emotion Lexicon, the comments are categorized into positive, negative, or neutral sentiments.
Network Analysis – A graph-based approach is used to visualize relationships between comments, distinguishing between original comments and replies while identifying key discussion trends.
# Approach
## Data Collection:
Comments were extracted from the YouTube interview using web scraping techniques.
The dataset was preprocessed by removing spam, duplicates, and irrelevant text.

## Sentiment Analysis:
Implemented VADER (Valence Aware Dictionary and sEntiment Reasoner) for sentiment scoring.
Used NRC Emotion Lexicon to classify emotions such as anger, joy, and surprise.
Compared the results to identify whether the general sentiment leaned positive, negative, or neutral.

## Network Analysis:
Constructed a graph representation of the comments, where nodes represent comments and edges represent replies.
Analyzed word co-occurrence patterns to determine common discussion themes.
Visualized the hierarchical structure of discussions, highlighting dominant opinions and interaction clusters.

## Evaluation and Insights:
Identified a slight positive sentiment bias towards Andrew Tate.
Found a balanced mix of both supportive and critical viewpoints, indicating a diverse audience perspective.
Network analysis revealed clusters of engagement, with some topics receiving significantly higher interactions.

# Conclusion
This project demonstrates the effectiveness of sentiment and network analysis in understanding public opinion. While the YouTube comments on the interview indicate a general positive inclination towards Andrew Tate, broader conclusions require further analysis across multiple platforms. Future work could expand the study to Twitter, Reddit, and other social media channels to obtain a more comprehensive sentiment distribution.
