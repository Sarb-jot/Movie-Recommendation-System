# Movie-Recommendation-System
This is a content-based Movie Recommendation System built using Python. It takes user preferences and recommends similar movies based on textual features such as genres, keywords, overview, cast, and crew.

📌 Features
✅ Recommends top 5 similar movies based on content similarity

🔍 Uses cosine similarity on combined metadata

🧠 Leverages NLP techniques like TF-IDF and Count Vectorization

📂 Interactive Jupyter Notebook format

📁 Project Structure
Copy
Edit
movie_recommendation_system/
├── movie recommendagion sysytem.ipynb
├── dataset/
│   └── movies.csv
├── README.md
📚 Dataset
The system uses a dataset typically sourced from TMDb (The Movie Database) that includes:

Movie titles

Overview

Genres

Keywords

Cast and crew

You can replace or expand the dataset (movies.csv) with a richer one for improved recommendations.

🧠 How It Works
Preprocessing: Cleans and combines features like overview, genres, keywords, cast, and crew.

Vectorization: Applies CountVectorizer to convert text into numeric vectors.

Similarity Calculation: Computes cosine similarity between movie vectors.

Recommendation: Given a movie name, the system returns the top 5 most similar movies.

🚀 Getting Started
🔧 Requirements
Install the required libraries:

bash
Copy
Edit
pip install numpy pandas scikit-learn nltk
▶️ Run the Notebook
Open movie recommendagion sysytem.ipynb in Jupyter Notebook or VS Code.

Run all cells.

Use the recommend() function to get movie suggestions.

Example:

python
Copy
Edit
recommend("Avatar")
💡 Example Output
markdown
Copy
Edit
Top 5 Movies similar to Avatar:
1. Guardians of the Galaxy
2. Star Wars: The Force Awakens
3. Interstellar
4. The Avengers
5. Star Trek Into Darkness
   
🛠 Future Improvements
Add a web interface using Streamlit or Flask

Include collaborative filtering

Use BERT or other advanced NLP models for semantic understanding

📃 License
This project is open-source and free to use for educational purposes.
