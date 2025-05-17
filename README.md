# ai-debris-tracking
🚀 AI-powered space debris tracking and satellite collision prediction using TLE data, orbital mechanics, and machine learning.
# 🌌 AI-Powered Space Debris Tracking and Collision Prediction

This project leverages Artificial Intelligence and Machine Learning to detect potential collisions between satellites and space debris in Earth's orbit. Using publicly available orbital data (TLE - Two Line Element), we simulate satellite orbits, compute relative distances, and predict high-risk collision events.

## 🚀 Why This Project?

As more satellites are launched into space, the risk of in-orbit collisions increases, threatening global communication, navigation, and observation systems. By applying AI to space situational awareness, this project aims to:
- Predict close approaches or possible collisions
- Improve satellite safety through early warnings
- Contribute to sustainable and safe space operations

## 🧠 Core Features

- Parse and simulate orbits using TLE data
- Compute satellite positions with `Skyfield`
- Engineer features such as relative velocity, altitude, and distances
- Train machine learning models (e.g., Random Forest, LSTM) for collision risk prediction
- Visualize orbits and predicted events (optional: via Streamlit dashboard)

## 🛠 Technologies Used

- Python
- Machine Learning (Scikit-learn, TensorFlow)
- Orbital Mechanics (Skyfield, SGP4)
- Data Processing (NumPy, Pandas)
- Visualization (Matplotlib, Plotly)
- Dashboard (optional: Streamlit)

## 📊 Dataset

- TLE (Two Line Element) datasets from:
  - [Celestrak](https://celestrak.org/)
  - [Space-Track](https://www.space-track.org/)
  - NASA public satellite data

## 🗂️ Folder Structure
