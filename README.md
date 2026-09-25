# OpenSource Compass

An ML-based GitHub repository recommendation system that recommends
repositories based on their descriptions, topics, and domains.

## Current Approach

Repository metadata
→ Text preprocessing
→ TF-IDF
→ Cosine similarity
→ Top-N recommendations

## Evaluation

The baseline recommender achieved 74% Mean Precision@5
on a manually annotated evaluation set of 20 query repositories.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Cosine Similarity

## Project Status

Currently developing the recommendation pipeline and interactive
application.
