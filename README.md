# Extracting-images-from-a-pdf
Problem:extract images from PDF

How to tackle the problem

Simple analogy of the solution to the problem

We will extract the images from PDF files and save them using PyMuPDF library.


Step to step way of tackling a problem.

Import necessary libraries
    • Specify the path of the file from which you want to extract images and open it
    • Iterate through all the pages of PDF and get all images objects present on every page
    • Use getImageList() method to get all image objects as a list of tuples
    • To get the image in bytes and along with the additional information about the image, use extractImage()
NB : PyMuPDF is used to access PDF files.
