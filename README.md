<h1 align="center">
MoodSync-Your Emotion-Driven Spotify Player :musical_note: :sparkles:
</h1>

<!--[Project Logo](path_to_logo.png) (Optional: Include a logo or relevant image for your project)-->
![MoodSync](https://github.com/Prajjwal-Chauhan/Sentisonics_Your-Emotion-Driven-Spotify-Player/assets/83890311/f8791afe-9d76-45a0-a581-d3b0c0602500)


## :muscle: Introduction

Welcome to MoodSync, where emotions meet music! 🎵 :heart_eyes: MoodSync is a powerful project that uses the magic of computer vision and deep learning to detect your emotions in real-time using your device camera. With seven mood categories including 😡 angry, 😢 sad, 😖 disgust, 😄 happy, 😨 fear, 😲 surprise, and 😐 neutral, we'll curate the perfect Spotify playlists that match your every emotion!

## :sparkles: Features

- Real-time emotion detection using your device camera.
- Accurate identification of seven distinct moods: 😡 angry, 😢 sad, 😖 disgust, 😄 happy, 😨 fear, 😲 surprise, and 😐 neutral.
- Seamless integration with the Spotify API for personalized song recommendations.
- Instantly opens the Spotify app with the perfect playlist based on your mood.
- User-friendly interface with real-time visual feedback. :camera: :notes:

## :rocket: Technologies Used

- TensorFlow with Keras: For building and training the Convolutional Neural Network (CNN) model for emotion detection.
- OpenCV: For real-time video capture and processing to recognize your mood.
- JSON: For data serialization and seamless integration with the Spotify API.
- Spotipy: For interacting with the Spotify API to gather song recommendations and open the Spotify app.
- Webbrowser Library: For opening a new window and taking you directly to your personalized Spotify playlist.
- Python: The beating heart of this project. :snake:

## :gear: Installation

Getting started with Sentisonics is a breeze! Simply follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries using the following command:
   ```
   pip install tensorflow keras opencv-python spotipy
   ```

## :key: Configuration

Before you start using Sentisonics, make sure to set up your Spotify API credentials. To do this, you'll need to create a Spotify Developer account and create a new project in the Spotify Developer Dashboard. Once you have your account and project set up, obtain the following credentials:

- **Username**: Your Spotify username, which will be used to access your playlists and listen history.
- **Client ID**: This unique identifier is required to authenticate your requests to the Spotify API.
- **Client Secret**: A secret key associated with your Client ID for secure authorization.

Once you have obtained these credentials from the Spotify Developer Dashboard, update the `.ipynb` file in the Sentisonics project under `Spotify setup and integration` section with your credentials. This will enable Sentisonics to access your Spotify account and personalize the music recommendations based on your preferences.

## :musical_score: Let the Emotions Unleash!

With your Spotify API credentials all set, you are now ready to experience the enchanting world of Sentisonics! :tada: Launch the application, let the camera capture your emotions, and immerse yourself in a curated musical journey that resonates with your feelings. Whether you're feeling pumped up, reflective, or anything in between, Sentisonics will always have the perfect playlist ready for you. :headphones: Enjoy the music that mirrors your soul! :sparkles:

## :video_camera: Walkthrough Video

[Click here](https://www.linkedin.com/posts/prajjwal-chauhan-0a4ba820a_sentisonics-emotiondrivenmusic-musiclovers-activity-7088111147278622720-kGyJ?utm_source=share&utm_medium=member_desktop) to check out the Walkthrough video.


## :raised_hands: Contributing

We welcome all contributors to enhance Sentisonics and make it even more magical. If you have any suggestions, find bugs, or want to add exciting new features, feel free to submit a pull request or open an issue in the repository. Together, let's make Sentisonics the ultimate emotion-driven Spotify player! :rocket:

## :page_facing_up: License

Sentisonics is released under the [GNU GPLv3.0 License](LICENSE). 
