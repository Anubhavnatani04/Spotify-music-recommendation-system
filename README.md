# Spotify Music Recommendation System

This project is a Spotify music recommendation system that provides personalized song recommendations based on user input. It combines content-based and popularity-based approaches to suggest songs that are similar in musical characteristics and have high popularity scores.

## Getting Started

To get started with this project, follow the instructions below:

### Prerequisites

Before running the code, make sure you have the following prerequisites installed:

- Python 3.x
- Required Python packages (you can install them using `pip`):
  - `requests`
  - `base64`
  - `pandas`
  - `spotipy`
  - `scikit-learn`

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/spotify-music-recommendation.git
   cd spotify-music-recommendation
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Obtain Spotify API credentials:
   - Create a Spotify Developer account and create a new application to get your `CLIENT_ID` and `CLIENT_SECRET`.
   - Replace the placeholders in the code with your actual credentials:

   ```python
   CLIENT_ID = "Your client id"
   CLIENT_SECRET = "Your secret code"
   ```

2. Run the Python script:

   ```bash
   python spotify_recommendation.py
   ```

   - The script will prompt you to paste the link to a Spotify playlist. It will then recommend songs based on the playlist and your input.

## Features

- **Content-Based Recommendations:** The system uses musical features such as danceability, energy, and tempo to recommend songs similar to the input song.

- **Popularity-Based Recommendations:** The system considers the popularity of songs and their release dates to provide relevant recommendations.

- **Hybrid Recommendations:** A combination of content-based and popularity-based recommendations to offer a balanced set of suggestions.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add a new feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Create a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This project uses the [Spotipy](https://spotipy.readthedocs.io/en/2.18.0/) library to interact with the Spotify API.

## Contact

If you have any questions or suggestions, feel free to contact the project owner:

- Anubhav Natani
- anubhavnatani10@gmail.com
- Project Link: (https://github.com/Anubhavnatani04/spotify-music-recommendation)
```

Make sure to replace `"Your client id"` and `"Your secret code"` with your actual Spotify API credentials. Additionally, update the contact information and other placeholders as needed.
