# 🎬 Movie Recommendation System

My **second Machine Learning project** as a fresher, built to understand how recommendation systems work using Python and basic NLP techniques.

This project recommends movies similar to a movie selected by the user based on its **genre and overview**.

## 🧠 About the Project

I built this project as a **Content-Based Movie Recommendation System**.

The model does not use user ratings or personal profiles. Instead, it compares the information available about movies and finds movies with similar content.

For example:

```python
recommend_movies("Grave of the Fireflies")
```

returns a list of movies that are considered similar based on the available movie information.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* CSV Dataset

## 🤖 Machine Learning Techniques Used

The main techniques used in this project are:

* **CountVectorizer** — converts movie text into numerical features.
* **Cosine Similarity** — calculates how similar two movies are.
* **Content-Based Filtering** — recommends movies based on their content.

The main information used for recommendations is:

* Movie Genre
* Movie Overview

## 📊 Dataset

The project uses a `movies.csv` dataset containing movie information such as:

* Movie ID
* Title
* Genre
* Overview
* Original Language
* Popularity
* Release Date
* Vote Average
* Vote Count

## 📂 Project Structure

```text
Movie-Recommendation-System/
│
├── model.ipynb
├── movies.csv
└── README.md
```


## 📚 What I Learned

Through this project, I learned how to:

* Work with a real-world movie dataset
* Clean and prepare text data
* Use Pandas for data manipulation
* Convert text into numerical features
* Apply Cosine Similarity
* Build a basic recommendation system
* Understand how content-based recommendation works
* Debug and improve a machine learning project

This project is part of my journey of learning **Machine Learning and Python**, and it is my **second ML project**.

## 👨‍💻 Author

**Nemora**

*Machine Learning Fresher | Learning by Building Projects*
