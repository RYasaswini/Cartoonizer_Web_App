# Cartoonify & Image Styling Effect

A Flask web application that allows users to apply various artistic effects to their images using OpenCV in Python. Users can easily transform their photos into cartoons, sketches, and other styles, making image editing fun and accessible.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Future Enhancements](#future-enhancements)
- [References](#references)

## About the Project
This project is designed to provide a simple, user-friendly platform for applying artistic effects to images. The application lets users upload their photos and apply a variety of styles, such as cartoon effects, pencil sketches, and watercolor effects. The goal is to make image editing fun and easy for everyone, even those without technical knowledge.

## Features
- **Cartoon Effect**: Transforms photos into a cartoon-like style with bold outlines and vibrant colors.
- **Pencil Sketch**: Converts photos into pencil sketches, offering both grayscale and colored options.
- **Watercolor Effect**: Adds a soft, dreamy effect to photos, making them resemble watercolor paintings.
- **Detail Enhancement**: Enhances fine details, making images appear sharper and more defined.

## Tech Stack
- **Backend**: Flask, Python
- **Frontend**: HTML, CSS (Bootstrap)
- **Image Processing**: OpenCV

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RYasaswini/Cartoonizer_Web_App.git
   cd Cartoonizer_Web_App
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
3.Run the application
   python app.py

## Usage
1.Open the application in your browser.
2.Upload an image using the provided form.
3.Select the desired artistic effect (e.g., cartoon, sketch, watercolor).
4.Click the "Stylize" button to apply the effect.
5.The modified image will be displayed and can be downloaded.

## Folder Structure
- **static/**: Contains CSS files and other static resources for the web app’s UI.
- **templates/**: HTML templates for the application.
- **uploads/**: Stores images uploaded by users.
- **cartoon_images/**: Stores the processed images after applying effects.

## Future Enhancements
- **Additional Effects**: Add more artistic styles, such as oil painting, 3D effects, and abstract art.
- **User Accounts**: Enable users to save their favorite styles and edited images.
- **Mobile Version**: Develop a mobile-friendly version for easy access on smartphones.
- **Community Features**: Create a space for users to share their edited images with others.
