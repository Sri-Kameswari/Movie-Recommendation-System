# Movie Recommendation System
This project aims to build a movie recommendation system using content based machine learning technique. The system processes and analyzes movie data to recommend similar movies based on a given input.

## Project Flow
1. Data Collection
2. Data Pre-processing
3. Building the ML Model
4. Creating the Website

## Working
1. Data Import - Data is imported from the TMDB 5000 movie dataset (available on Kaggle).
2. Data Cleaning - Remove attributes such as revenue, release date, runtime, etc.
3. Data Preprocessing
   - Convert all text to lowercase.
   - Remove all punctuations and non-word characters (special symbols, etc.).
   - Remove stop words (are, the, is, etc.).
   - Apply stemming to reduce words to their root form.
5. Building the Model
    - Concatenate tags from the dataset.
    - Build a dataframe that records the frequency of tags.
    - Transform each row into a vector.
    - Use an N-dimensional vector space for cosine similarity to calculate distances between vectors.

## Tech Stack
- Python: The primary programming language for data processing and model building.
- Streamlit: Used for creating the web application.
- DataSet: TMDB 5000 movie dataset from Kaggle.
- Development Tools: Jupyter Notebook and PyCharm.

 ## Contributing
Feel free to submit issues and pull requests. Contributions are welcome!

![Screenshot](https://github.com/user-attachments/assets/6819387a-1e38-4ede-a448-6c47bdff89c1)
