# Sign Language to Text and Speech Conversion

This project aims to convert sign language gestures captured via a webcam into text and then into speech.

## Project Overview

The application uses computer vision and machine learning techniques to recognize hand gestures representing letters or words in sign language. These recognized gestures are then translated into text, and a text-to-speech engine is used to voice the output.

## Features (Implemented/Planned)

*   Real-time hand gesture recognition from webcam feed.
*   Conversion of recognized gestures into text.
*   Speech output for the converted text.
*   User interface to display the video feed, recognized characters, and the constructed sentence.
*   Suggestions for words based on recognized characters.

## Setup and Installation

1.  **Clone the repository (once uploaded to GitHub):**
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Create a Python virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## How to Run

After completing the setup, run the main application script:

```bash
python3 final_pred.py
```

## Dependencies

Key dependencies include:
*   OpenCV
*   TensorFlow/Keras
*   MediaPipe
*   cvzone
*   pyttsx3
*   NumPy
*   PyEnchant

(A full list is in `requirements.txt`)

## Model

The project uses a pre-trained model (`cnn8grps_rad1_model.h5`) for gesture classification.

## Future Enhancements
*   Improve model accuracy and expand the range of recognized signs.
*   Support for different sign languages.
*   More robust word suggestion and sentence completion. 