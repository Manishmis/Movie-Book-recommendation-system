# Movie-Book-recommendation-system

# Recommendation System

A content-based and collaborative filtering recommendation engine for movies.

## Features
- **Content-Based Filtering**: Recommends similar items using TF-IDF and cosine similarity.
- **Collaborative Filtering**: Recommends items based on user behavior (KNN).

## Usage
```bash
# Content-based
python scripts/content_based.py

# Collaborative filtering
python scripts/collaborative_filtering.py
```

## Results
| Algorithm               | Example Recommendation for "Inception" |
|-------------------------|---------------------------------------|
| Content-Based           | The Matrix, Interstellar, Tenet       |
| Collaborative Filtering | The Dark Knight, Shawshank Redemption |

## Future Improvements
- Hybrid recommendation system.
- Deploy with Flask/Django.
- Use deep learning (Neural Collaborative Filtering).
