# Constellation-Finder

**Constellation-Finder** is an AI-powered image processing tool designed to identify and analyze constellations within astronomical images. By leveraging advanced image processing techniques and augmentation methods, the tool provides a robust solution for recognizing and matching constellation patterns, making it ideal for educational and research purposes.

## **8CD - 8 Constellation Dataset**
The dataset is organized within the `8CD` folder. This folder contains all the images and resources used in this project (including augmented images).

## Key Features

- **Constellation Detection**: Identifies constellations in images using **template based matching** and feature detection algorithms.  
- **Image Augmentation**: Applies various transformations such as noise addition, brightness adjustment, skewing, and perspective changes to enhance dataset variability.  
- **Interactive Directory Selection**: Users can easily select directories for input and output images via an intuitive dropdown interface.  
- **Dynamic Progress Tracking**: Displays real-time progress for processing templates, ensuring efficient workflow monitoring.  
- **Comprehensive Results**: Outputs top constellation matches along with visualization and detailed metrics.  

## Technical Details

### Frontend  

- **Interactive Widgets**: Utilizes IPyWidgets for dropdown selection and progress visualization.  
- **Dynamic Feedback**: Provides user-friendly, real-time updates on directory validation and image processing.  

### Backend  

- **Framework**: Python-powered backend with OpenCV for image processing and augmentation.  
- **Template Matching**: Employs ORB feature detection, FLANN-based matching, and homography techniques for accurate results.  
- **Augmentation Techniques**: Includes scaling, rotation, noise addition, blur, skew, color jitter, and perspective transformations to improve model robustness.  

### Data Processing  

- **Custom Dataset**: Processes images from directories into augmented versions for training and testing.  
- **Top Match Ranking**: Computes and ranks the top-3 constellation matches with detailed scoring and probability measures.

## Motivation

**Constellation-Finder** was developed to make constellation identification accessible and efficient for astronomy enthusiasts, educators, and researchers. Its goal is to simplify the process of detecting and analyzing celestial patterns while providing tools for dataset enhancement and visualization. By combining technical precision with ease of use, the tool bridges the gap between amateur and professional astronomy applications.

The project emphasizes accuracy, flexibility, and user-friendliness, enabling anyone to explore and study constellations.

## Clone the repository:
  ```bash
  git clone https://github.com/AFLucas-UOM/Constellation-Finder.git
  ```

## Acknowledgments

This project was developed as part of the `ICS3206` course at the `University of Malta`.

## Contact

For inquiries or feedback, please contact [Andrea Filiberto Lucas](mailto:andrealucasmalta@gmail.com)