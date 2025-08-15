🎬 Movie Recommendation System — Task 5 (Elevvo Pathways)
📌 Overview

As part of Task 5 in the Elevvo Pathways Program, I developed a Movie Recommendation System using the MovieLens 100K dataset.
This project explores collaborative filtering techniques, matrix factorization, and evaluation metrics to deliver accurate, personalized movie suggestions.

🛠 Tools & Libraries

Python 🐍

Pandas 📊

NumPy 🔢

Scikit-learn 🤖

📚 Topics Covered

Recommendation Systems

Similarity-Based Modeling

Matrix Factorization (SVD)

Model Evaluation (Precision@K)

🚀 Features
1️⃣ User-Based Collaborative Filtering

Creates a user–item matrix from ratings data.

Computes cosine similarity between users.

Recommends unseen movies based on top-N similar users.

2️⃣ Precision@K Evaluation

Measures accuracy by checking how many recommended movies are relevant (rating ≥ 4).

3️⃣ Item-Based Collaborative Filtering (Bonus)

Computes item–item similarity to recommend movies similar to ones already liked.

4️⃣ Matrix Factorization with SVD (Bonus)

Uses Truncated SVD to uncover hidden patterns in the rating matrix.

Predicts ratings for unseen movies.

📊 Workflow

Load Dataset → MovieLens 100K

Preprocess Data → Build user–item matrix, fill missing values

Compute Similarity → User–user & item–item cosine similarity

Generate Recommendations → Top-K suggestions

Evaluate → Precision@K score

Matrix Factorization → SVD-based recommendations
