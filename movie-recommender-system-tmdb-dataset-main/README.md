🎬 Movie Recommender System

A simple Movie Recommendation Web App built with Streamlit and powered by machine learning similarity scores.
The app suggests movies similar to your favorite one and also displays their posters using The Movie Database (TMDb) API.

🚀 Features

🔎 Search any movie from the list

🎯 Get top 5 similar recommendations instantly

🖼️ Movie posters displayed for better experience

🌐 Powered by TMDb API for posters and metadata

⚡ Fast and interactive UI using Streamlit

🛠️ Tech Stack

Python 3.8+

Streamlit
 – Web App framework

Pickle
 – To load pre-trained models

Requests
 – For API calls

TMDb API – For fetching movie posters

📂 Project Structure
├── model/
│   ├── movie_list.pkl       # Pickle file containing movie data
│   ├── similarity.pkl       # Pre-computed similarity matrix
├── 83acbbaf-16a0-4d37-940b-6e1d1a46d8db.py   # Main Streamlit app
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/vijethh-ai1/movie-recommender-system.git
cd movie-recommender-system

2️⃣ Install dependencies
pip install -r requirements.txt


If requirements.txt is missing, install manually:

pip install streamlit requests

3️⃣ Run the Streamlit app
streamlit run app.py

🖼️ Demo

Select a movie from the dropdown

Click "Show Recommendation"

Get 5 similar movies with posters 🎉

🔑 API Key Setup

The app uses the TMDb API. Replace the API key inside fetch_poster function if needed:

url = f"https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY&language=en-US"


➡️ Get your free API key here: TMDb API

📌 Example Output
Selected Movie: Inception
Recommendations:
1. Interstellar
2. The Prestige
3. The Dark Knight
4. Memento
5. Tenet


With posters displayed side by side ✅

🤝 Contributing

Contributions are welcome!

Fork this repo

Create a new branch (feature-xyz)

Commit changes and push

Submit a pull request

📜 License

This project is licensed under the MIT License.
Feel free to use and modify.

👨‍💻 Author

Developed with ❤️ by Vijeth Naik
