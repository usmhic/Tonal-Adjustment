# A Comprehensive Guide with a Demonstration of using Point Operators in Image Processing.

Point operators are essential image processing transforms that allow modification of output pixel values based solely on the corresponding input pixel value and, in some cases, global parameters or information. Examples of point operators include brightness and contrast adjustments, color correction, and color transformations, all of which are referred to as point processes in the image processing literature.

This project provides a practical and theoretical exploration of point operators, starting with the theoretical aspect that demonstrates these transforms using Python and OpenCV in Jupyter notebooks. The practical part is a tonal adjustment web app built with Python’s libraries: Flask and Pillow that enables users to upload an image and apply these transforms to modify exposure, contrast, highlights, shadows, whites, and blacks. In the future, we plan to integrate AI and add an auto-tonal adjustment feature.

## Repository Contents
The GitHub repository mentioned above contains Jupyter notebooks for each image processing transform mentioned, providing a practical and interactive way to learn and experiment with these transforms. Each notebook provides an explanation of the transform and its practical applications, along with detailed code examples that include step-by-step instructions for applying the transformation to images.

The notebooks in the repository cover the following image processing transforms:

1. Pixel transforms: This notebook covers brightness scaling, contrast adjustments, and image addition.
2. Color Transforms: This notebook covers color correction and transformations, including hue, saturation, and value adjustments.
3. Compositing & Matting: This notebook covers image compositing and matting operations that are widely used in computational photography and computer graphics.
4. Histogram Equalization: This notebook covers the more global process of histogram equalization, which adjusts the distribution of pixel values in an image.

# Usage
To use the notebooks, you can either clone the repository or download the files directly from GitHub. Then, open the desired notebook in Jupyter and follow the instructions provided to learn and experiment with the various transforms.

# Contributing
Contributions to the repository are welcome. If you would like to add a new notebook or make changes to an existing one, please create a pull request and we will review it as soon as possible.

# License
This project is licensed under the MIT License. Please see the LICENSE file for more information.
