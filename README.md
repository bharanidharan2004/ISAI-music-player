
# ISAI: Intelligent Music Player

[](https://www.google.com/search?q=LICENSE)
[](https://www.google.com/search?q=https://github.com/bharanidharan2004/ISAI-Player/stargazers)

## ✨ What is ISAI?

**ISAI** (**I**ntelligent **S**ound **A**nalysis **I**nterface) is a modern desktop music player that organizes your personal music collection by **mood**, not just by traditional tags like artist or genre.

It was built to give you dynamic, context-aware playlists by listening to the actual sound of your songs.

### 📌 Key Features

  * **Smart Playlist Curation:** Uses Machine Learning (**K-Means Clustering**) to sort songs into 5 distinct, automatic mood categories.
  * **Audio Feature Analysis:** Employs the **`librosa`** library to analyze the sonic DNA of each track (tempo, spectral characteristics).
  * **Simple Desktop UI:** Easy-to-use graphical interface built with Python's **`tkinter`**.
  * **Full Playback Controls:** Includes Play/Pause, Skip, Previous, and 10-second Seek (Forward/Rewind).

-----

## 💻 Technologies Used

This project is a powerful desktop application built entirely with Python and several advanced data science and audio libraries.

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **User Interface** | **Python `tkinter`** | Creates the simple, interactive graphical application window. |
| **Audio Analysis** | **`librosa`** | Core library for extracting audio features (tempo, tone, energy). |
| **Machine Learning** | **`scikit-learn` (`KMeans`)** | Algorithm used to automatically find and group similar-sounding songs. |
| **Music Playback** | **`pygame`** | Handles loading, playing, and controlling the music files. |

-----

## 🚀 How to Get Started

These instructions will get the music player running on your local machine.

### 📋 Prerequisites

You must have the following installed on your computer:

  * **Python:** Version 3.8 or higher.
  * **Your own collection of music files** (supports `.mp3`, `.m4a`, `.flac`, `.wav`).

### 🛠️ Installation

1.  **Clone the Repository:** Download the project files using the command line:
    ```bash
    git clone https://github.com/bharanidharan2004/ISAI-Player.git
    cd ISAI-Player
    ```
2.  **Install Libraries:** Install all necessary Python libraries (you may need a `requirements.txt` file for this, otherwise install the main libraries manually: `pip install pandas numpy librosa scikit-learn pygame tk`):
    ```bash
    # Assuming you have a requirements.txt file:
    pip install -r requirements.txt
    ```

-----

## 🏃 How to Use ISAI

### 1\. Launch the Application

Start the player by running your main Python file:

```bash
python [your_main_file_name].py
```

### 2\. Analyze Your Music

1.  Click the **"Select Music Folder"** button.
2.  Choose the main folder containing your music files.
3.  ISAI will begin the **Analysis** process. The progress bar will show the status as it analyzes each song and applies machine learning.
      * *Note: The first analysis can take several minutes depending on your music library size.*

### 3\. Play by Mood

Once analysis is done, the player view appears:

1.  Use the **"Select Mood"** dropdown box to choose a category (e.g., "Workout & Energy" or "Acoustic & Calm").
2.  The player will instantly start playing a randomly shuffled playlist of songs that fit that acoustic mood.

-----

## 👤 Author

**Bharanidharan T**

  * **GitHub:** [github.com/bharanidharan2004](https://www.google.com/search?q=https://github.com/bharanidharan2004)
  * **Email:** tbharani0005@gmail.com

-----

## 🔑 License

This project is licensed under the **MIT** License. See the `LICENSE` file for details.
