# Task 5: Movie Recommendation System

## Project Overview
Implemented a content-based movie recommendation system using TMDB movie dataset, utilizing natural language processing and cosine similarity.

## Key Features
1. **Data Processing**
   - Merged movies and credits datasets
   - Extracted key features: genres, keywords, cast, crew, overview
   - Handled missing values and duplicates

2. **Text Processing**
   - Converted text data to lowercase
   - Applied stemming for text normalization
   - Combined features into unified tags
   - Removed stop words

3. **Feature Engineering**
   - Extracted top 3 cast members
   - Identified movie directors
   - Combined multiple text features into a single tag
   - Created text vectors using CountVectorizer

4. **Recommendation Engine**
   - Implemented cosine similarity for movie comparison
   - Created recommendation function
   - Returns top 5 similar movies

## Technical Stack
- Python 3.x
- pandas: Data manipulation
- numpy: Numerical operations
- nltk: Text processing
- scikit-learn: Feature extraction and similarity calculation

## Data Sources
- TMDB 5000 Movies Dataset
  - Movie details (tmdb_5000_movies.csv)
  - Movie credits (tmdb_5000_credits.csv)

## Implementation Steps
1. Data Loading and Merging
2. Feature Selection and Cleaning
3. Text Processing
4. Vector Creation
5. Similarity Calculation
6. Recommendation Function

## Usage
```python
# Example usage
recomandation('Avatar')  # Returns 5 similar movies
```

## Model Details
- Uses CountVectorizer with 5000 features
- Implements cosine similarity for movie comparison
- Considers multiple aspects: plot, genre, cast, crew

## Results
The system provides personalized movie recommendations based on:
- Content similarity
- Genre matching
- Cast and crew overlap
- Plot similarities
