# YOLO Object Detection Web App - Detecting people in a video / cctv / webcam

This repository contains a web application for object detection using the YOLO (You Only Look Once) deep learning model. The primary purpose of this application is to detect and count people in video streams. The YOLO model has proven to be an efficient and accurate solution for object detection tasks, making it suitable for this project.

## Features

- Detect and count people in video streams.
- User-friendly web interface for easy interaction.
- Can be used to count people in webcam also by changing few lines of code. 

## Prerequisites

Before using the application, ensure you have the following dependencies installed:

- Python 3.8+
- Flask - a Python web framework.
- OpenCV - for image and video stream processing.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Viserion-7/Object-Detection-using-yolov8.git
```
2. Create a virtual environment:

 ```bash
 python3 -m venv venv
```

3. Install the required Python packages:

```bash
pip install -r requirements.txt
```

4. Run the web application:

```bash
python app.py
```

The app should now be accessible in your web browser at `http://localhost:5000`.

## Usage

1. Open the web application in your browser.

2. Choose a video file to process for real-time detection.

3. Click the "Upload" button to display the video with the object detection process.

4. The application will display the processed image or video with bounding boxes around detected people, along with the count.

## Customization

- Modify the HTML and CSS files in the `templates` and `static` directories to change the appearance and layout of the web application.

- Add additional features or object classes to the application as needed.

- Edit this [line](https://github.com/Viserion-7/Object-Detection-using-yolov8/blob/main/app.py#L36-L37) to switch between webcam and uploading video mode.
