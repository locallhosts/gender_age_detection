# Age-Gender Detector
This Python application detects faces in a video stream and predicts the 
age and gender of each person.

# Installation
To run this application, you can either install the dependencies locally 
or use Docker.

# Local installation
To install the dependencies for this application, run the following 
command:

**pip install opencv-python**

# Docker installation
To install and run the application using Docker, you need to have Docker 
installed on your system.

Create a file named requirements.txt in the root directory of your 
project, containing the single line:

**opencv-python**

Build the Docker image by running the following command in the same 
directory as your Dockerfile:

**docker build -t age-gender-detector .**

bash:
**Run the Docker image using the following command:**



his will start a container running your Python app inside the Docker 
image, and you can interact with it as normal.

# Usage
To run the application, execute the following command:

**python face_age_gender_detection.py**



This will open a video stream and display the age and gender predictions 
for each detected face.

To quit the application, press the 'q' key.

# Credits
This application was created for purpose of education **ISAIAH OBOH**

Feel free to modify and use this code for your own projects.
