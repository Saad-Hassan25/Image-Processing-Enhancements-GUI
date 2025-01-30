# Image Processing with Interpolation Algorithms and GUI

This project demonstrates image enlargement and interpolation algorithms implemented from scratch using Python. It includes the design of a GUI that allows the user to interact with the image processing functions, such as enlarging an image with different interpolation methods and applying linear interpolation.

## Features

- **Image Enlargement**:
    - **Zero-order Hold**: Enlarges the image by replicating pixel values.
    - **First-order Hold**: Enlarges the image by interpolating between adjacent pixels.

- **Linear Interpolation**: Allows the user to input a scale factor (K) to resize the image with linear interpolation.

## Requirements

- Python 3.x
- Tkinter (for GUI)
- Pillow (for image processing)
- NumPy (for numerical operations)

To install the necessary dependencies, run:

```bash
pip install tkinter pillow numpy
