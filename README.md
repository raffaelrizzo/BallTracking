# Footbonaut2GO

This repository hosts an interesting project divided into two parts - one part is dedicated to ball detection using Python and OpenCV, and the second part is about a Unity project called MR Footbonaut. These two parts communicate with each other using UDP protocol, forming a complex and exciting VR-enabled application.

## Requirements

Before getting started, ensure you have the following software and hardware requirements:

### Software
1. **Python**: The scripts are written in Python. Make sure you have Python 3.6 or later installed on your machine.
2. **OpenCV**: This is used for real-time computer vision.
3. **TensorFlow**: It's utilized for the Ball Detection Model.
4. **Argparse**: Used for command-line option and argument parsing.
5. **Socket**: Enables the network connections.
6. **NumPy**: Fundamental package for scientific computing with Python.
7. **Unity**: Needed to run the MR Footbonaut project.
8. **UDP_Receiver Unity Script**: Handles the transfer of position data via UDP.

### Hardware
1. **VR Headset**: With passthrough enabled.

## Installation

Here are the steps to install the necessary libraries and dependencies:

1. **Python**
   
   Python can be installed from the official website: https://www.python.org/downloads/

2. **OpenCV, TensorFlow, Argparse, Socket, NumPy**

   These Python libraries can be installed using pip. Run the following command in your terminal:

   ```shell
   pip install opencv-python tensorflow argparse socket numpy
   ```

3. **Unity**
   
   You can download and install Unity from its official site: https://unity.com/download

4. **Clone this repository**

   Navigate to your desired directory via terminal and clone this repository with the command:

   ```shell
   git clone <repository_url>
   ```

## How to Run

Here's the step-by-step process to get the project up and running:

1. **Update the IP Address**
   
   Both the Python script and the UDP_Receiver script that is attached to the Sphere in the Unity scene require the IP address. Make sure to update the IP address in both scripts accordingly.

2. **Run the Ball Detection Script**
   
   Navigate to the "BallDetection Python" folder in your terminal and run the "BallDetection_4Point_Calibration_2Cameras_dynamic" script:

   ```shell
   python BallDetection_4Point_Calibration_2Cameras_dynamic.py
   ```

3. **Open the Unity Scene**
   
   Now, navigate to the "MR Footbonaut" folder and open the "Dynamic_Footonaut.unity" scene.

4. **Run the Unity Scene**
   
   With the Unity scene open, and your VR headset with passthrough enabled, press the Play button in Unity to run the scene.

Congratulations! You are now operating a complex VR application, capable of detecting ball positions in real-time and immersing you in the virtual MR Footbonaut experience.

## Summary
This repository represents a proof of concept that demonstrates the power and possibility of combining real-time image processing with mixed reality. However, as it stands, the implementation requires two powerful computers and two cameras to function effectively. An intriguing direction for future exploration would be how to streamline and optimize image processing techniques to be more suitable and efficient for mixed reality applications.

## Acknowledgements
We would like to express our profound gratitude to our Professor Philippe Colantoni for providing invaluable guidance this project. 

If you have any issues or feedback, please open an issue on this GitHub repository. Contributions are also welcome! Please feel free to fork this repository and submit a pull request with your changes. Happy coding!
