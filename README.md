# 🎬 Movie Recommendation System

This project is a **Movie Recommendation System** that suggests movies to users based on similarity scores computed from movie metadata.

## 📂 Project Structure

```
├── app.py                # Main Streamlit app script
├── model/                # Folder containing ML models and serialized files
│   └── similarity.pkl    # Precomputed similarity matrix (large file, excluded from GitHub)
├── notebooks/            # Jupyter notebooks for experimentation
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## 🚀 Features
- Content-based movie recommendation system.
- Precomputed similarity matrix for fast recommendations.
- Interactive user interface built with **Streamlit**.

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/bikramcodes/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app.py
   ```

## 📊 Dataset
The dataset used for training is the **TMDB 5000 Movie Dataset**, containing metadata such as cast, crew, keywords, and genres.

- You can download the dataset from Kaggle: [TMDB 5000 Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 🖼️ Screenshots
_Add demo screenshots of your app UI here_

## 🔮 Future Improvements
- Add collaborative filtering for personalized recommendations.
- Deploy the app using **Streamlit Cloud** or **Heroku**.
- Integrate more advanced NLP-based embeddings for better accuracy.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

💡 *Built with ❤️ by Bikram Singh*
