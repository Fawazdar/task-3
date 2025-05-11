
# MovieLens Recommender System

This project is a simplified recreation of a user-based collaborative filtering recommender system using a simulated MovieLens-style dataset.

## 🔍 Overview

The system analyzes user ratings for movies and computes user-user similarity using cosine similarity. Based on this similarity, it recommends movies to a target user that were highly rated by similar users.

## 📁 Files

- `movielens_recommender.py`: Main Python script for building the recommender system and visualizing user similarity.
- `user_similarity_heatmap.png`: Heatmap image showing cosine similarity between users.

## ⚙️ Features

- Creates a user-item rating matrix.
- Computes user similarity using cosine similarity.
- Recommends top-N movies for a target user.
- Visualizes the similarity matrix with a heatmap.

## 🚀 How to Run

1. Clone the repository.
2. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3. Run the script:
    ```bash
    python movielens_recommender.py
    ```

## 📊 Example Output

- User 1 receives a recommendation for Movie 40.
- A heatmap image (`user_similarity_heatmap.png`) is generated.

## 👤 Author

- GitHub Username: `yourusername`
- Task completed as part of a data-driven UX assignment.

## 📚 References

- Harper, F. M., & Konstan, J. A. (2015). *The MovieLens Datasets: History and Context*. ACM Transactions on Interactive Intelligent Systems, 5(4), 1–19.
- GroupLens Research. (n.d.). [MovieLens](https://movielens.org/)
- Scikit-learn: [https://scikit-learn.org](https://scikit-learn.org)
