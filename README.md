# AI Generated ActivityClip Extractor

Welcome to the **AI Generated ActivityClip Extractor** repository! This module is designed to enhance video analysis by automatically extracting specific segments based on user-defined descriptions. Leveraging advanced machine learning models, this tool identifies activities within video frames, compares them to textual input, and clips the video to provide focused content that matches the user's interest.

## Features

- **Activity Detection**: Uses a pre-trained MobileNetV2 model to generate captions for video frames.
- **Semantic Analysis**: Employs BERT from Hugging Face's transformers to analyze semantic similarity between generated captions and user input.
- **Video Clipping**: Clips and saves segments of the video that match the described activity.

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- TensorFlow
- OpenCV
- PIL (Pillow)
- NumPy
- Transformers
- MoviePy

## Installation

Clone the repository and set up the required environment:

```bash
git clone https://github.com/SyedAhsanIqbal/AI-Generated-ActivityClip-Extractor.git
cd AI-Generated-ActivityClip-Extractor
pip install tensorflow opencv-python-headless pillow numpy transformers moviepy
