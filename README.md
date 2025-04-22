# 🎬 Netflix Movie Recommendation System

This project builds a hybrid movie recommendation system using the Netflix Prize dataset. It combines collaborative filtering (SVD), content-based filtering (TF-IDF), and a hybrid recommender, and deploys the system using Streamlit with an interactive UI.

## 🚀 Features

- **Collaborative Filtering** with SVD, KNN, and NMF
- **Content-Based Filtering** using TF-IDF on movie titles
- **Hybrid Recommender** that blends both approaches
- **Streamlit App** for interactive recommendations
- **Model Evaluation** using RMSE and MAE metrics
- **Sample Recommendations** generated dynamically
- **Ngrok + Colab Integration** for live app previews

## 🧠 Technologies Used

- Python, Pandas, NumPy
- Scikit-Learn, Surprise
- TF-IDF (sklearn), Cosine Similarity
- Streamlit
- Ngrok (for public Colab deployment)
- Pickle / Dill for model serialization

## 📊 Dataset

Netflix Prize Dataset:  
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

- 100M+ ratings
- 480,000+ users
- 17,000+ movies

## 📦 How to Run

1. Clone the repo and open the notebook (`Netflix_recommendation.ipynb`)
2. Train the models and export them as `.pkl`
3. Run the `app.py` using Streamlit
4. Use Ngrok or local port forwarding to access the live UI

## 🔍 Sample Screenshot

![streamlit preview](assets/screenshot.png)

## 📄 License

This project is for educational and portfolio purposes.
