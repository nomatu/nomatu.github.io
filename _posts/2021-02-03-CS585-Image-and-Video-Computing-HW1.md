---
layout: post
title: "CS585 Image and Video Computing HW1"
date: 2021-02-03
---
![Photo of myself](Photo.jpg "Original Image")
![Grey version](gray.jpg "Greyscale Image") 
![Blur version](blur.jpg "Blurred Image") 


For Homework 1, I created two algorithms to the greyscale image and blurred image. For the greyscale image, I calculated the sum of the product of 3D matrix of image values and the 3D matrix containing the following numbers: 0.07, 0.72, 0.21. 
Then, the output matrix is converted to absolute values of the elements.
For the blurred image, I ran the image though a box filter, with the box kernel being set to a 19 x 19 array with 1/19 value in each element of the array.
