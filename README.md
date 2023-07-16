# Handwritten-Word-Detection
 I create a Deep learning model to detect handwritten words starting from a digit recognition model and updating and modifying it 


This program allows you to classify handwritten characters using a trained deep learning model. It provides a graphical user interface (GUI) where you can upload an image containing a handwritten character, and the program will classify the character and display the predicted label.

## Prerequisites

To run this program, you need to have the following dependencies installed:

- Python 3.x
- tkinter module (`pip install tkinter`)
- PIL (Python Imaging Library) module (`pip install pillow`)
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- Keras (`pip install keras`)

## Getting Started

1. Clone or download the program files to your local machine.

2. Ensure that you have a trained model file (e.g., `model_hand.h5`) available in the same directory as the program files.

3. Run the program using a Python interpreter.

   ```
   python character_classification.py
   ```

## Usage

1. When the program starts, a GUI window will appear.

2. Click on the "Upload an image" button to select an image file (e.g., a handwritten character) from your local machine.

3. The program will display the uploaded image in the GUI window.

4. Click on the "Classify Image" button to classify the handwritten character in the uploaded image.

5. The program will apply pre-processing steps to the image, resize it, and pass it through the trained model for classification.

6. The predicted label for the character will be displayed in the GUI window.

7. You can upload and classify multiple images consecutively by repeating steps 2-6.

8. To exit the program, close the GUI window.

## Notes

- Ensure that you have a trained model file (e.g., `model_hand.h5`) available in the same directory as the program files. You can train your own model or obtain a pre-trained model from a reliable source.

- The program uses the Keras library to load the trained model for character classification. Make sure you have the `keras` library installed and compatible with your Python environment.

- The program supports classification for uppercase English alphabets (A-Z). You can modify the `word_dict` dictionary to include additional characters or modify the labels as per your requirements.

- Adjustments to the GUI layout, button styles, or other elements can be made in the code based on your preferences.


## Acknowledgments

- This program utilizes a trained deep learning model to classify handwritten characters.

- The tkinter module provides the GUI functionalities to upload images and display results.

- The PIL (Python Imaging Library) and OpenCV libraries are used for image processing and visualization.

- The Keras library provides the tools for loading and using the trained model for classification.

- Special thanks to the developers and contributors of the mentioned libraries and tools for making this program possible.
