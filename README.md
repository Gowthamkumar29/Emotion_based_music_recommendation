# 🎧 Emotion-Based Music Recommendation System

This project detects human emotions from facial expressions using **DeepFace** and recommends music that matches the user's mood, playing the song directly through your **Spotify** account. It combines computer vision with music intelligence to deliver a personalized audio experience.

---

## 🚀 Features

- 🎭 Real-time facial emotion detection using webcam
- 🤖 Emotion classification (happy, sad, angry, etc.)
- 🎵 Mood-based music recommendation
- 🔗 Spotify integration for instant music playback
- 🌐 Flask-based web application with user-friendly interface

---

## 📸 Demo Screenshots

### 🎯 Emotion Detection in Action  
![Emotion Detection](screenshots/emotion-detection.png)

### 🎧 Spotify Preview of Recommended Song  
![Spotify Preview](screenshots/spotify-preview.png)

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python, Flask  
- **Libraries & APIs**:
  - [DeepFace](https://github.com/serengil/deepface)
  - [OpenCV](https://opencv.org/)
  - [Spotipy (Spotify API)](https://spotipy.readthedocs.io/)
  - Pandas

---

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Gowthamkumar29/Emotion_based_music_recommendation.git
cd Emotion_based_music_recommendation

2. Create a Virtual Environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Setup Spotify API Credentials
Visit the Spotify Developer Dashboard

Create an app to get your Client ID and Client Secret

Create a new file named config.py in the root directory and add:
SPOTIPY_CLIENT_ID = 'your-client-id'
SPOTIPY_CLIENT_SECRET = 'your-client-secret'
SPOTIPY_REDIRECT_URI = 'http://localhost:8888/callback'

5. Run the App
.\run_app.ps1
Visit in browser: http://127.0.0.1:5000/

🧠 Detected Emotions
-😊 Happy

-😭 Sad

-😡 Angry

-🤯 Surprise

-😑 Neutral

-😱 Fear

-🤢 Disgust

📚 References
DeepFace Documentation

Spotify Web API

OpenCV Face Detection

🙌 Acknowledgements
This project was inspired by the intersection of AI and music.
Built to showcase practical applications of Machine Learning and Full-Stack Development.

