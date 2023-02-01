# Image Processing - Finding Shape Corners and Area

## Introduction

This repository contains a solution to find the corners of an object in an image using the Sobel Edge Detector and Thresholding, and then use these corners to calculate the area of the object.

## Sobel Edge Detector and Thresholding

The Sobel Edge Detector is used to find the edges of an object in an image, and Thresholding is used to convert the image into binary, where the object is represented in white and the background in black. The edges and corners of the object can then be easily extracted from the binary image.

## Finding the Corners of a Shape

Once the edges of an object have been found, the corners of the shape can be extracted using the Harris corner detection algorithm. This algorithm calculates the Harris corner response for each pixel in the image, which represents how well the pixel can be considered a corner, and then selects the pixels with the highest response as the corners of the shape.

## Calculating the Area of a Shape

Once the corners of the shape have been found, the area of the shape can be calculated by finding the convex hull of the corners. The convex hull is the smallest convex polygon that contains all the corners, and its area can be easily calculated from the number of corners and their positions.

## Usage

The code in this repository can be run on an input image to find the corners of an object and display the area of the object. The thresholding and Harris corner detection parameters can be adjusted to achieve the best results.

## Conclusion

This solution provides a simple and effective way to find the corners and area of an object in an image using the Sobel Edge Detector and Thresholding. By adjusting the parameters, the solution can be adapted to work with a wide range of object shapes and sizes.
