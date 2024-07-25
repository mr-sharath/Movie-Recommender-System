
# Movie Recommender System Based on Wikipedia Links 🎬

Welcome to the Movie Recommender System project! This repository demonstrates a novel approach to movie recommendations using outgoing Wikipedia links. By extracting and analyzing these links, we build a recommender system that provides movie suggestions based on their connections and embeddings.

## Project Overview 🚀

In this project, you will:

1. **Extract Training Data**: Collect a dataset from Wikipedia, focusing on outgoing links related to movies.
2. **Train Embeddings**: Create movie embeddings using these links to capture the relationships between films.
3. **Build a Classifier**: Implement a Support Vector Machine (SVM) classifier to recommend movies based on the embeddings.
4. **Predict Review Scores**: Use the embeddings to predict and evaluate movie review scores.

## Getting Started 🛠️

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required libraries: `numpy`, `scikit-learn`, `keras`, `beautifulsoup4`, `mwparserfromhell`

### Installation

Clone this repository and install the required packages:

```bash
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system
pip install -r requirements.txt
```

### Usage

1. **Data Extraction**: Run `data_extraction.py` to gather the dataset from Wikipedia.
2. **Training Embeddings**: Execute `train_embeddings.py` to create movie embeddings.
3. **Build and Train Classifier**: Use `build_classifier.py` to train the SVM model.
4. **Predict Scores**: Run `predict_scores.py` to predict movie review scores.

### Example

Here is an example of how to find similar movies:

```python
from movie_recommender import recommender

similar_movies = recommender.get_similar_movies('Rogue One')
print(similar_movies)
```

## Project Structure 📁

- `data_extraction.py`: Extracts and preprocesses data from Wikipedia.
- `train_embeddings.py`: Trains movie embeddings using Wikipedia links.
- `build_classifier.py`: Builds and trains the SVM classifier.
- `predict_scores.py`: Predicts movie review scores.
- `movie_recommender.py`: Contains core functionalities for the recommender system.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## ©️ Copyright

© 2024 Sharath Kumar Reddy. All rights reserved.

---

Feel free to contribute, open issues, or suggest improvements! 😊✨

---

**Contact:**
Sharath Kumar Reddy  
Email: skreddykapu@uh.edu  
LinkedIn: [Sharath Kumar Reddy](https://linkedin.com/in/sharath-kumar-reddy)  
Portfolio: [mr-sharath.github.io](https://mr-sharath.github.io)
