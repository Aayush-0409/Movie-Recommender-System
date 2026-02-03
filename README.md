📽️ End-to-End Movie Recommendation System

Built with NLP, TF-IDF & FastAPI

This project implements a full-stack, content-based movie recommendation system using Natural Language Processing (NLP), Term Frequency-Inverse Document Frequency (TF-IDF) vectorization, and a modern FastAPI backend. It demonstrates how to build a real-world API that serves intelligent movie suggestions based on text-based movie metadata — ideal for learning recommendation systems and deploying scalable ML-powered services

🚀 Features

🎯 Content-Based Filtering
Uses TF-IDF to represent movie features (e.g., titles, descriptions) as vectors and computes similarity to suggest relevant movies.

🧠 NLP-Driven Recommendations
Applies text preprocessing and vectorization to extract meaningful patterns from movie metadata.

⚡ FastAPI Backend
Exposes a RESTful API to serve movie recommendations with high performance and scalability.

🔍 TF-IDF + Cosine Similarity
Calculates semantic similarity between movies for personalized suggestions.


🧩 Tech Stack
Layer	Technologies
Machine Learning :	Python, Scikit-learn, NLP
Vectorization	: TF-IDF (Term Frequency–Inverse Document Frequency)
Similarity : Cosine Similarity
Backend	: FastAPI


💡 How It Works :-

Data Preparation
Movie metadata (e.g., title, description) is preprocessed and cleaned.

TF-IDF Vectorization
Text is transformed into numerical feature vectors capturing semantic importance.

Similarity Computation
Movie similarity is computed using cosine similarity on TF-IDF vectors.

API Endpoint
A FastAPI endpoint takes user input (movie name) and returns recommendations.
