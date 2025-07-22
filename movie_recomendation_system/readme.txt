 🎬 Movie Recommendation System

A content-based movie recommendation system that suggests similar movies based on the user's choice. Built using Python, Pandas, Streamlit and optionally fetches posters using the TMDB API for a visual experience.

---

 🔍 Features

- 🔗 Recommends top 5 similar movies based on content similarity
- 🎞️ Displays movie posters (via TMDB API)
- 🖥️ Simple and interactive web UI using Streamlit
- 💾 Uses precomputed similarity matrix for fast recommendations

---

 📂 Project Structure

movie-recommendation-system/
├── app.py # Main Streamlit app
├── movies.pkl # Movie list & metadata
├── similarity.pkl # Precomputed similarity matrix
├── requirements.txt # Python dependencies
\── README.md # Project overview (this file)




---

 🚀 How to Run Locally

1. **Clone the Repository**

git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
Install Dependencies


pip install -r requirements.txt
Run the App


streamlit run app.py


🛠️ Tech Stack
Python 🐍

Pandas & NumPy 📊

Scikit-learn 🤖

Streamlit 🌐

TMDB API 🎞️ (for posters)

📌 Requirements
All dependencies are listed in requirements.txt, but key libraries include:

streamlit

pandas

scikit-learn

requests

📜 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Abhang Vijay Vyawhare
📧 vyawhareabhang@gmail.com
🌐 LinkedIn | GitHub

⭐️ Show Your Support
If you found this project useful, give it a ⭐ on GitHub and share it with others! Contributions and suggestions are welcome!


