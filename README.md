# RGB Channel Viewer with Three.js

This project provides an interactive visual tool to explore the RGB color channels of an image using Three.js. The tool separates an image into its Red, Green, and Blue (RGB) channels, displays them as individual layers, and allows users to manipulate the channel positions in 3D space. Users can upload their own images to see how each channel contributes to the overall image.

## Features

1. **Image Upload**: Allows users to upload their own image for processing.
2. **RGB Channel Separation**: The image is split into its Red, Green, and Blue channels.
3. **Interactive Controls**:
   - Adjust the Z-axis separation to see the layers in depth.
   - Adjust the X-axis side-by-side positioning for a clearer comparison of channels.
4. **Dynamic Texture Loading**: The application dynamically generates textures for each channel using the uploaded image.
5. **3D Visualization**: The Three.js library is used to render the channel layers in a 3D environment with smooth interaction.

## How to Use

1. Either Go to the github page link or clone the repository for local usage
2. Use the "Upload Image" button to upload your own image.
3. Adjust the sliders to manipulate the channel layers in 3D space.

## Demonstrating Linear Algebra and Matrices in Image Processing

This project is an excellent tool for demonstrating how linear algebra and matrices are used in image processing. Here's how it connects to the subject:

### 1. **Image as Matrices**
An image can be represented as a collection of matrices:
- Each color channel (Red, Green, and Blue) is stored as a 2D matrix of pixel intensities.
- The overall image is a combination of these three matrices.

### 2. **Channel Separation**
When separating channels, the image matrix is split into three separate matrices:
- Red Matrix: Contains pixel values for the red intensity.
- Green Matrix: Contains pixel values for the green intensity.
- Blue Matrix: Contains pixel values for the blue intensity.

This project visualizes these separated matrices as individual textures applied to planes in 3D space.

### 3. **Matrix Transformations**
The project can be extended to demonstrate various matrix operations, such as:
- **Applying Filters**: Filters like Gaussian blur, edge detection, or sharpening can be applied by convolving the image matrix with a kernel (another matrix).
- **Scaling and Translation**: Manipulating the sliders demonstrates how matrices can be transformed in 3D space, similar to transformations in linear algebra.
- **Channel Combination**: The original image can be reconstructed by combining the individual channel matrices.

### 4. **Practical Applications**
This visualization can be used to explain the following:
- **Image Filters**: Demonstrate how image filters (like grayscale conversion, edge detection, or thresholding) are applied to individual channels or the combined image.
- **Color Manipulation**: Modify the values in each channel to change the color composition of the image.
- **Image Compression**: Teach concepts like PCA (Principal Component Analysis) by reducing redundancy in color channels.
