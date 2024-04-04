# Image Editor - A Python Image Editing Application

This is a Python application for basic image editing functionalities. It utilizes the `customtkinter` library for a sleek and modern user interface, and leverages the Pillow library (`PIL Fork`) for image manipulation tasks.

## Features

* Import images in various formats (e.g., JPG, PNG)
* Rotate and zoom images
* Flip images horizontally, vertically, or both
* Adjust image brightness, vibrance, and sharpness
* Apply grayscale and invert color effects
* Apply blur and contrast filters
* Choose from various effects like emboss, find edges, contour, and edge enhance
* Export edited images with desired name, format (JPG or PNG), and save location

## Usage

1. **Installation:**
    * Ensure you have Python 3.x installed on your system.
    * Install the required libraries:
        ```bash
        pip install customtkinter Pillow
        ```
2. **Running the application:**
    * Open a terminal or command prompt and navigate to the directory containing this project's code.
    * Run the main script using the following command:
        ```bash
        python app.py
        ```
    * The application window will launch, allowing you to interact with the image editing features.

## Code Structure

The code is organized into several modules:

* `app.py`: The main application script that initializes the user interface and functionalities.
* `panels.py`: Contains code for various UI elements like sliders, dropdown menus, and buttons used for editing options.
* `settings.py`: Stores constants used throughout the application, such as color themes and default values for image manipulation.
* `image_widgets.py`: Provides classes for handling image import, output canvas, and closing the editing window.
* `menu.py`: Implements the tabbed menu structure for accessing different editing functionalities.

## Dependencies

* `customtkinter`: https://github.com/TomSchimansky/CustomTkinter (Customizable Tkinter theme engine)
* `Pillow (PIL Fork)`: https://pillow.readthedocs.io/ (Python Imaging Library)

## Contributing

Feel free to fork this repository and contribute improvements or new features. 


