# 🎬 Movie Recommendation System

This project is a **Movie Recommendation System** that suggests movies to users based on similarity scores computed from movie metadata.

## 📂 Project Structure

```
RECOMMENDATION SYSTEM/
│
├── data/                     # Raw dataset
│   ├── credits.csv
│   └── movies.csv
│
├── model/                    # Saved models (Pickle files)
│   ├── movie_list.pkl
│   └── similarity.pkl
│
├── notebooks/                # Jupyter notebooks
│   └── data_exploration.ipynb
│
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── .gitignore
```

## 🚀 Features
- Content-based movie recommendation system.
- Precomputed similarity matrix for fast recommendations.

## 🛠️ Tech Stack
- Python
- Libraries:
   - Pandas
   - Numpy
   - Scikit-learn
   - Pickle

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

## ⚡ Workflow
1. Data Preprocessing
   - Selected significant columns (title, genres, keywords, overview, cast & crew).
   - Extracted main names from cast & crew details.
   - Removed spaces in multi-word entities to create tokens.
   - Split text into lists of strings.

2. Feature Engineering
   - Merged relevant columns into a new column context.
   - Created sentences from context for vectorization.
   - Applied Bag of Words (CountVectorizer) to generate vectors.

3. Model Building
   - Calculated cosine similarity between movies.
   - Built a function to recommend top similar movies given a title.


## 🔮 Future Improvements
- Add collaborative filtering for personalized recommendations.
- Deploy the app using **Streamlit Cloud** or **Heroku**.
- Integrate more advanced NLP-based embeddings for better accuracy.
- Hybrid recommendation (content + collaborative)

## 📊 Example Output
🎬 Input Movie: Avatar
✨ Recommended Movies:
1. John Carter
2. Guardians of the Galaxy
3. Star Trek
4. The Fifth Element
5. Interstellar

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

💡 *Built with ❤️ by Bikram Singh*
