# OpenCV Face And Eye Detection In Flask Web Framework

This project is a real-time face and eye detection web application built using Python, OpenCV, and Flask. The application captures video from your webcam, detects faces and eyes using Haar Cascade classifiers, and streams the annotated video to a web page.

## Features

- Real-time face detection
- Eye detection within detected faces
- JPG video stream served via Flask
- Simple HTML interface for displaying the video

## Installation

1. **Clone the repository** or download the files:

    ```bash
    git clone https://github.com/Satvik-ai/OpenCV_Face_And_Eye_Detection_In_Flask_Web_Framework.git
    cd OpenCV_Face_And_Eye_Detection_In_Flask_Web_Framework-main
    ```

2. **Create a virtual environment (optional):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Ensure you have the following Haar cascade files in a `Haarcascades/` folder:**

    - `haarcascade_frontalface_default.xml`
    - `haarcascade_eye.xml`

    You can download them from the [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades).

## Usage

1. **Run the Flask application:**

    ```bash
    python app.py
    ```

2. **Visit the application in your browser:**

    ```
    http://127.0.0.1:5000/
    ```

## Reference

[Reference](https://github.com/krishnaik06/Flask-Web-Framework/tree/main/Tutorial%207)
