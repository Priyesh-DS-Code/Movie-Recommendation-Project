# 🎬 Movie Recommendation System

## Overview

Movie Recommendation System is a Machine Learning project that recommends movies similar to a user's selected movie using Content-Based Filtering techniques.

The system analyzes movie metadata and computes similarity scores to identify and recommend movies with similar characteristics. This project demonstrates the practical application of recommendation systems, feature engineering, similarity computation, and interactive deployment.

---

## Business Problem

With thousands of movies available across streaming platforms, users often struggle to discover content that matches their interests.

Recommendation systems help solve this problem by:

* Improving user experience
* Increasing user engagement
* Enhancing content discovery
* Providing personalized recommendations

This project aims to build an intelligent recommendation engine capable of suggesting relevant movies based on user preferences.

---

## Dataset Information

The project utilizes movie metadata obtained from TMDB datasets.

### Features Used

* Movie Title
* Genres
* Keywords
* Cast
* Crew
* Overview

### Target

Generate top movie recommendations based on similarity scores.

---

## Key Highlights

* End-to-End Recommendation System
* Content-Based Filtering
* Feature Engineering
* Similarity Computation
* Interactive Web Application
* Real-Time Recommendations

---

## Tech Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Machine Learning

* Scikit-Learn

### Natural Language Processing

* Text Vectorization
* Cosine Similarity

### Deployment

* Streamlit

### Version Control

* Git
* GitHub

### Future Deployment Stack

* Docker
* AWS

---



## Recommendation Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Text Processing
        ↓
Vectorization
        ↓
Similarity Matrix Creation
        ↓
Movie Recommendation
```

---

## Data Preprocessing

The following preprocessing steps were performed:

* Dataset merging
* Handling missing values
* Feature selection
* Metadata extraction
* Text cleaning
* Tag creation
* Feature aggregation

These steps help create meaningful movie representations for similarity analysis.

---

## Feature Engineering

Relevant movie attributes were combined into a unified feature set:

* Genres
* Keywords
* Cast
* Crew
* Movie Overview

The combined metadata was transformed into numerical vectors for similarity computation.

---

## Recommendation Engine

The recommendation engine follows these steps:

1. User selects a movie.
2. System locates the selected movie in the dataset.
3. Similarity scores are retrieved from the precomputed similarity matrix.
4. Movies are ranked based on similarity.
5. Top recommendations are returned to the user.

---

## Machine Learning Approach

### Content-Based Filtering

The recommendation system suggests movies based on similarity between movie metadata rather than user ratings.

Advantages:

* Personalized recommendations
* No dependency on user history
* Effective for new users
* Easy interpretability

---

## Application Features

* Interactive movie selection
* Real-time recommendations
* Fast similarity-based search
* User-friendly Streamlit interface
* Scalable recommendation pipeline

---

## Results

The system successfully recommends movies with similar genres, themes, cast members, and storylines.

The recommendation quality demonstrates the effectiveness of content-based filtering techniques in solving real-world recommendation problems.


---

## Installation

### Clone Repository

```bash
git clone https://github.com/Priyesh-DS-Code/Movie-Recommendation-System.git
```

### Navigate to Project Directory

```bash
cd Movie-Recommendation-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app.py
```

Application will be available at:

```text
http://localhost:8501
```

---

## Skills Demonstrated

* Machine Learning
* Recommendation Systems
* Feature Engineering
* Natural Language Processing
* Similarity Computation
* Data Preprocessing
* Streamlit Deployment
* Software Engineering
* Python Development

---

## Author

### Priyesh Kumar Kashyap

Machine Learning & Data Science Enthusiast focused on building end-to-end machine learning solutions and production-ready AI applications.

**Areas of Interest**

* Machine Learning
* Data Science
* MLOps


**Connect With Me**

GitHub: https://github.com/Priyesh-DS-Code

LinkedIn: https://www.linkedin.com/in/priyeshkumarkashyap
