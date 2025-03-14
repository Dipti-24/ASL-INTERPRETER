# ASL-Interpreter

## Overview
ASL interpreter that uses a webcam to detect and recognize hand gestures. It is built using TensorFlow, MediaPipe, and OpenCV. The model classifies ASL alphabet signs (A-Z) and displays the corresponding letter on the screen.

## Features

1. Real-time hand gesture detection using MediaPipe.

2. ASL alphabet recognition (A-Z letters).

3. Train and load a custom TensorFlow model.

4. Visual feedback on the webcam.

## Dataset

+ Source: ASL Alphabet Dataset from kaggle

+ Contains 87,000+ images (29 classes: A-Z, Space, Delete, Nothing).

## Installation

1. Ensure you have Python 3.10+ installed.

2. Clone the repository:

  + git clone https://github.com/Dipti-24/ASL-TRANSCRIPTION/.git
    
  + cd ASL-TRANSCRIPTION

3. Create a virtual environment (optional but recommended)

4. Install dependencies:

+ pip install -r requirements.txt

 ## Usage Instructions

1. Train the model or use the provided one.

2. Run the interpreter and show ASL gestures (A-Z) clearly to the webcam.

3. The corresponding letter will appear on the screen in real-time.
   
## TECH STACK

1. Python 

2. TensorFlow

3. OpenCV

4. MediaPipe
   
5. NumPy

## How It Works

**1. Model Training**: If an ASL model does not exist (asl_model.h5), the script trains a new model using images in the asl_alphabet directory.

**2. Hand Detection:** Uses MediaPipe to detect hand landmarks from the webcam feed.

**3. Gesture Classification:** The detected hand region is resized and classified by the CNN model.

**4. Real-Time Display:** The recognized ASL gesture is displayed on the webcam frame in real-time.


## License

This project is licensed under the [MIT License]().

## Contact

For questions, reach out at: mishradipti2402@gmail.com


