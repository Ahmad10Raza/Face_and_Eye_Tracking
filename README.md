Face and Eye Tracking using OpenCV

![Demo GIF](demo.gif)

This project demonstrates real-time face and eye tracking using OpenCV, a popular computer vision library. It utilizes Haar Cascade Classifiers for face and eye detection and basic tracking.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- OpenCV (install using `pip install opencv-python`)
- Webcam (for real-time tracking)

## Installation

To get started with this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Ahmad10Raza/Face_and_Eye_Tracking.git
   cd Face_and_Eye_Tracking
   ```
2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the face and eye tracking program, execute the following command:

```bash
python face_eye_tracking.py
```

Press the 'Esc' key to exit the program.

## How it Works

1. The program uses Haar Cascade Classifiers for face and eye detection, which are provided by OpenCV.
2. It captures video from your webcam and converts each frame to grayscale for detection.
3. The program detects faces within the frames, drawing rectangles around them.
4. For each detected face, it extracts the region of interest (ROI) and detects eyes within that ROI.
5. Rectangles are drawn around detected eyes as well.
6. The program continuously displays the video feed with detected faces and eyes.

## Demo

You can see the project in action in the [Video Link](https://drive.google.com/file/d/1TRWptLkiG-ntyOVAH3Dc1lhPEu_EwRTp/view?usp=sharing).

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please open an issue or a pull request.
