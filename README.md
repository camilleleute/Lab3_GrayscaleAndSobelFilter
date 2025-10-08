# Lab3_GrayscaleAndSobelFilter
Appling a grayscale and the Sobel filter frame by frame to a video file

## Overview
It’s time to start writing some application code on the Raspberry Pi! In this lab, you will be writing a C program that applies grayscale and the Sobel Filter frame by frame to a video file! What video file? That’s your choice, just grab a video file that’s compatible with OpenCV! You'll be compiling and running this code on your Raspberry Pis, so you may wish to write the code on your pi too! Fortunately you'll find all of your favorite Linux code editors (or, at least, VIM and Emacs) are available through the apt repo on your Pi (sudo apt install -y emacs vim).

## Assignment
Your task for this lab is to build and compile a program that pulls in frames from a video file, applies grayscale and Sobel to the frame and displays it. You will be processing one frame at a time until the video is done.

1. Create a to442_grayscale() function that uses the algorithm discussed in class to turn an OpenCV RGB Mat into a grayscale Mat. You may not use OpenCV’s built-in functions to do this conversion.
2. Create a to442_sobel() function that takes a grayscale Mat and returns a Mat with the Sobel filter applied using the algorithm and approximations discussed in class. Again, do not use any built-in Sobel functions from OpenCV, you must write the code to traverse the Mat manually.
3. Create a unified program that takes in a video file and processes it on a per frame basis. Each frame should have grayscale applied, followed by Sobel, and finally displayed to the user on screen.

## Deliverables
Demo step three to the professor (include a youtube or other video sharing link of your program running in your submissions). Submit all of your source code to Canvas. Please include both your name and your partner’s name in the document.