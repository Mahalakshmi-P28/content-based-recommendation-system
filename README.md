# Content-Based Recommendation System

## Project Description
This project is a content-based movie recommendation system built using Natural Language Processing (NLP) techniques, specifically TF-IDF vectorization and cosine similarity. It provides users with recommendations based on movie overviews. By leveraging NLP, the system can suggest movies that share similar content based on the descriptions provided.

## Purpose
The main purpose of this project is to develop a recommendation system that provides users with movie suggestions based on the content of the movies themselves. It analyzes the movie descriptions (overviews) and computes similarity scores to recommend similar movies.

## Key Features
- Content-based filtering: Recommends movies based on the similarity of their descriptions.
- TF-IDF Vectorization: Uses TF-IDF to transform movie overviews into numerical vectors for similarity calculation.
- Sigmoid Kernel: Applies the sigmoid kernel for similarity measurement between movie descriptions.

## Technologies Used
- Google Colab: The project was developed using Google Colab as the main platform.
- Python: The primary programming language.
- Scikit-learn: Used for TF-IDF vectorization and similarity computation.
- Pandas: Used for data manipulation.
- NumPy: Used for numerical operations.

## Accuracy
The system is capable of providing relevant movie recommendations based on their descriptions, with an effective similarity score helping to filter out less relevant suggestions.

## How to Run
1. Clone or download the repository.
2. Open the notebook in Google Colab or a local Python environment.
3. Run the code blocks sequentially to train the model and get recommendations.
4. To get movie recommendations, call the `give_rec()` function with the title of a movie.

## Installation
1. Clone the repository using Git:
    ```bash
    git clone https://github.com/your-username/repository-name.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
