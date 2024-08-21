# Music-Recommendation-System-using-Spotify-API-
This project showcases a Music Recommendation System that utilizes the Spotify API to fetch trending playlists and provides personalized music recommendations based on content-based and hybrid filtering techniques. The system is designed to recommend songs by analyzing various audio features and leveraging popularity metrics.

## 🚀 Features
#### Spotify Integration: 
Seamlessly integrates with Spotify to fetch data from trending playlists.

#### Content-Based Filtering: 
Recommends songs similar to the input track based on musical features such as danceability, energy, and tempo.

#### Hybrid Recommendations: 
Combines content-based filtering with a weighted popularity score for more refined recommendations.

#### Audio Feature Extraction: 
Extracts detailed audio features including danceability, energy, loudness, and more.

#### Playlist Data Analysis:
Analyzes and presents detailed information about tracks, including popularity and release dates.

## 🔧 Installation
Follow these steps to get the project up and running on your local machine:

#### Clone the Repository:
git clone https://github.com/Bajaj-Apurva/Music-Recommendation-System-using-Spotify-API-.git
cd Music-Recommendation-System-using-Spotify-API-

#### Spotify Developer Credentials:
You need to create a Spotify Developer account to generate your Client ID and Client Secret. Follow these steps:

Sign in to Spotify Developer: Go to the Spotify Developer Dashboard.

Create a New App:

Click on "Create an App".

Fill in the required fields (App name, description).

Get Client ID and Client Secret:

After creating the app, you'll see the Client ID and Client Secret on the app dashboard.

Add these to your environment variables or directly in the script.
Replace the placeholders in the code with your credentials

CLIENT_ID = 'your-client-id'
CLIENT_SECRET = 'your-client-secret'

## 🛠️ Usage
#### Content-Based Recommendations:
Use the content_based_recommendations function to get songs similar to the input track.

#### Hybrid Recommendations:
Utilize the hybrid_recommendations function to get more refined recommendations that take both content and popularity into account.

#### Data Analysis: 
Analyze the fetched playlist data using the Pandas DataFrame.

## 🧰 Technologies Used
Python: Primary programming language.

Spotipy: Python library for Spotify Web API.

Pandas: Data manipulation and analysis.

Scikit-Learn: Machine learning library for normalization and similarity calculations.

Spotify API: Used to fetch music data.

## 🛠️ How It Works
#### Access Token Generation:
The code generates an access token using your Client ID and Client Secret.
This token is required to make API calls to Spotify.

#### Data Fetching:
The code fetches tracks from a Spotify playlist and extracts relevant information like track name, artists, album, and various audio features.

#### Content-Based Filtering:
Songs are recommended based on their similarity to the input song's features (e.g., danceability, energy).

#### Hybrid Filtering:
Combines content-based filtering with a weighted popularity score to recommend songs that are both similar and popular.

## 🎯 Future Enhancements
#### User Authentication:
Implement OAuth2 for user-specific recommendations.

#### Collaborative Filtering:
Add collaborative filtering techniques to improve recommendation accuracy.

#### Web Interface:
Develop a web interface for easier interaction.

## 🤝 Contribution
Feel free to fork this repository, open issues, or submit pull requests if you have any suggestions or improvements.

## 📜 License
This project is licensed under the MIT License.

##  Acknowledgements
Spotify Web API

Spotipy
