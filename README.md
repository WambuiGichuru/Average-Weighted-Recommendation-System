# Average-Weighted-Recommendation-System 
# 📋 Project Overview 
This project implements a sophisticated movie recommendation system using content-based filtering. Unlike collaborative filtering that uses user behavior, this system analyzes movie content and features to find similar items. 

# 🎯 Features 
1. Content-Based Recommendations: Find movies similar to ones you like. 
2. Feature Engineering: Combines genres, keywords, cast, and director.  
3. NLP Techniques: Text processing and vectorization. 
4. Cosine Similarity: Mathematical approach to find similar movies. 

# 📁 Dataset 
The project uses the TMDB 5000 Movies Dataset containing: 
1. Movie titles and IDs. 
2. Genres, keywords, and overviews. 
3. Cast and crew information.
4. Vote counts and average ratings. 

# 📊 How It Works: 
1. Content-Based Filtering Concept
The system works by: 
- Creating Movie Profiles: Each movie is represented by its features (genres, cast, etc.). 
- Vectorization: Converting text features to numerical vectors. 
- Similarity Measurement: Using cosine similarity to find movies with similar vectors. 
- Recommendation: Returning the most similar movies. 

# Mathematical Foundation: 
Cosine Similarity: Measures the cosine of the angle between two vectors. 
Formula: cos(θ) = (A·B) / (||A|| * ||B||)  
Range: 0 (no similarity) to 1 (identical)  

# 💡 Key Insights: 
- No Cold Start Problem: Works well for new movies without rating history. 
- Transparent: Recommendations are based on actual movie features.  
- Niche Recommendations: Can find similar movies even if they're not popular.  