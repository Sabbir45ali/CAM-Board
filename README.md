# CAM BOARD

Welcome to the CAM BOARD project! This project leverages computer vision and hand-tracking technology to create a virtual drawing board using a webcam. Users can draw on the screen using different colors simply by moving their hands in front of the camera. The project utilizes OpenCV for image processing, MediaPipe for hand-tracking, and Python for implementation.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview
CAM BOARD is an interactive application that enables users to draw on a virtual canvas by detecting their hand movements in real-time through a webcam. The project is designed to be user-friendly and includes features such as multiple color selections and a clear screen functionality.

## Features
- **Real-time Hand Tracking**: Detect and track hand movements using the webcam.
- **Drawing Functionality**: Draw on the virtual canvas with your hand.
- **Multiple Colors**: Switch between different colors (blue, green, red, yellow) for drawing.
- **Clear Screen**: Clear the entire drawing canvas with a gesture.
- **User-friendly Interface**: Easy to use with intuitive controls.

## Technologies Used
- **Python**: Programming language used for implementation.
- **OpenCV**: Library for image processing.
- **MediaPipe**: Framework for hand-tracking.
- **NumPy**: Library for numerical operations.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Sabbir45ali/CAM-Board.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd CAM-BOARD
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python cam_board.py
    ```

## Usage

1. **Start the application**:
    - Run the Python script `cam_board.py`.
    - The webcam feed will open in a new window.

2. **Drawing**:
    - Use your index finger to draw on the canvas.
    - Move your hand to the color selection boxes at the top of the screen to switch colors.
    - To clear the screen, move your hand to the "CLEAR" box.

3. **Close the application**:
    - Press the 'q' key to exit the application.

## Contributing
We welcome contributions to enhance the CAM BOARD project. If you have suggestions or find any issues, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature/YourFeature
    ```
3. **Commit your changes**:
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature/YourFeature
    ```
5. **Open a pull request**.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
We would like to thank the open-source community for the invaluable resources and libraries that made this project possible. Special thanks to our mentors and peers for their support and feedback.
