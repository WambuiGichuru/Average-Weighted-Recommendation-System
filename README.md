# Average-Weighted-Recommendation-System 
# 📋 Project Overview 
This project implements a sophisticated movie recommendation system using content-based filtering. Unlike collaborative filtering that uses user behavior, this system analyzes movie content and features to find similar items. \n

# 🎯 Features 
1. Content-Based Recommendations: Find movies similar to ones you like. \n
2. Feature Engineering: Combines genres, keywords, cast, and director.  \n
3. NLP Techniques: Text processing and vectorization. \n
4. Cosine Similarity: Mathematical approach to find similar movies.  \n

# 📁 Dataset 
The project uses the TMDB 5000 Movies Dataset containing: \n
1. Movie titles and IDs. \n
2. Genres, keywords, and overviews. \n
3. Cast and crew information. \n
4. Vote counts and average ratings. \n

# 📊 How It Works: 
1. Content-Based Filtering Concept
The system works by: \n
- Creating Movie Profiles: Each movie is represented by its features (genres, cast, etc.). \n
- Vectorization: Converting text features to numerical vectors. \n
- Similarity Measurement: Using cosine similarity to find movies with similar vectors. \n
- Recommendation: Returning the most similar movies. \n

# Mathematical Foundation: 
Cosine Similarity: Measures the cosine of the angle between two vectors. \n
Formula: cos(θ) = (A·B) / (||A|| * ||B||)  \n
Range: 0 (no similarity) to 1 (identical)  \n

# 💡 Key Insights: 
- No Cold Start Problem: Works well for new movies without rating history. \n
- Transparent: Recommendations are based on actual movie features.  \n
- Niche Recommendations: Can find similar movies even if they're not popular.  \n