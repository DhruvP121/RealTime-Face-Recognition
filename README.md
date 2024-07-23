# OpenCV Image and Video Processing

This repository contains scripts for various image and video processing tasks using OpenCV and PIL. The scripts include functionalities for face detection, cartoonifying images, and color detection.

## Prerequisites

Ensure you have the following libraries installed:

- OpenCV
- Pillow (PIL)
- `utils` module (this should include a function `get_limits` for color detection)

You can install the required packages using pip:

pip install opencv-python-headless pillow

# Menu Options
Face Detection (Image): Detects faces in a given image and displays the image with rectangles drawn around detected faces.
Face Detection (Video): Detects faces in real-time from the webcam and displays the video with rectangles drawn around detected faces.
Cartoonify Image: Applies a cartoon effect to a given image and displays the original and cartoonified images.
Color Detection: Detects a specific color (yellow) in real-time from the webcam and draws rectangles around detected areas.
Exit: Exits the program.

# Functions
face_detection_image(image_path=None): Detects faces in a given image.
face_detection_video(): Detects faces in real-time from the webcam.
cartoonify_image(image_path): Applies a cartoon effect to a given image.
color_detection(): Detects a specific color (yellow) in real-time from the webcam.
File Descriptions
main.py: The main script containing the menu and function calls.
utils.py: A utility module that should include a get_limits function for color detection.
# Example
1.To run face detection on an image, select option 1 from the menu and provide the image path when prompted:
Enter your choice (1-6): 1
Enter the path of the image: path/to/your/image.jpg

2.To run face detection in real-time from the webcam, select option 2 from the menu:
Enter your choice (1-6): 2

3.To apply a cartoon effect to an image, select option 3 from the menu and provide the image path when prompted:
Enter your choice (1-6): 3
Enter the path of the image: path/to/your/image.jpg

4.To detect a specific color in real-time from the webcam, select option 4 from the menu:
Enter your choice (1-6): 4

