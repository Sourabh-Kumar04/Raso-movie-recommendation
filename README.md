# 🎬 Raso Movie Recommendation System

[![Streamlit App](https://img.shields.io/badge/Live%20App-Raso--Movie--Recommendation-brightgreen)](https://raso-movie-recommendation.streamlit.app/)

## 📌 Introduction
Raso Movie Recommendation System is a machine-learning-powered application that suggests movies based on user preferences. It leverages **collaborative filtering** and **content-based filtering** techniques to provide accurate recommendations.

## 🚀 Live Demo
Experience the app live at:  
🔗 **[Raso Movie Recommendation](https://raso-movie-recommendation.streamlit.app/)**

## 📂 Project Structure
```
.
├── app.py  # Main application file
├── movie-recommendation-system.ipynb  # Jupyter notebook for model training
├── similarity.pkl  # Precomputed similarity matrix
├── movie_dict.pkl  # Processed movie dictionary
├── movies.pkl  # Movie dataset
├── requirements.txt  # Required dependencies
├── start.sh  # Deployment script
├── tmdb_5000_credits.csv  # Movie credits dataset
├── tmdb_5000_movies.csv  # Movie metadata dataset
├── .gitattributes  # Git LFS tracking
├── .gitignore  # Files to ignore
├── LICENSE  # License information
├── README.md  # Documentation
└── vercel.json  # Deployment configuration
```

## 🛠️ Installation & Setup
### Clone the Repository
```sh
git clone https://github.com/Sourabh-Kumar04/Raso-movie-recommendation.git
cd Raso-movie-recommendation
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Run Locally
```sh
streamlit run app.py
```

## 📊 Features
✅ Movie recommendations based on similarity scores  
✅ User-friendly Streamlit UI  
✅ Uses **TF-IDF** and **cosine similarity** for recommendations  
✅ Deployed online for easy access  

## 🏗️ Built With
- **Python** 🐍
- **Streamlit** 🚀
- **Pandas, NumPy** 📊
- **Scikit-Learn** 🤖
- **Git LFS** (for large file handling)

## 📜 License
This project is licensed under the MIT License.

## 🌟 Acknowledgments
- **TMDB** for movie dataset
- **Streamlit** for web framework
- **Scikit-Learn** for ML algorithms

📧 **Developed by [Sourabh Kumar](https://github.com/Sourabh-Kumar04/)**

