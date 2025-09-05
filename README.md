# 🎬 Movie Recommendation System

This project is a **content-based movie recommendation system** that suggests movies similar to a user’s favorite choice. It uses **cosine similarity** and **text-based features** such as genres, keywords, cast, and crew.

## 🚀 Features

* Input your favorite movie and get **top 30 similar movies**.
* Uses **scikit-learn** for feature extraction and similarity calculation.
* Implemented in **Python** with a Jupyter Notebook (`.ipynb`).
* Interactive and easy to extend with new datasets.

## 📂 Project Structure

```
Movie_Recommendation_System/
│-- Movie_Recommendation_System.ipynb   # Main notebook
│-- movies.csv                          # Dataset (if used)
│-- README.md                           # Project documentation
```

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Difflib
* Jupyter Notebook

## 📊 How It Works

1. Load the movies dataset.
2. Preprocess and combine important features (title, genres, cast, crew, keywords).
3. Convert text features into vectors.
4. Compute **cosine similarity** between movies.
5. Ask the user for their favorite movie and recommend similar ones.

## ▶️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Neeha2704/Movie_Recommendation_System.git
   cd Movie_Recommendation_System
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Movie_Recommendation_System.ipynb
   ```

4. Enter your favorite movie when prompted and get recommendations.

## 📌 Example Output

```
Enter your fav movie name: Avatar

Movies Suggested for you:

1. Avatar  
2. Guardians of the Galaxy  
3. Star Wars: The Force Awakens  
4. The Avengers  
... up to 30 results

