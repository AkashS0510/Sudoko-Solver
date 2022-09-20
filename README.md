# Sudoko-Solver

Sudoko Image is read and the image is preprocessed to detect the contours of the Sudoko.
The Contour of the Sudoko is then converted into bird's eye view to get the good angle of the image.
Each Cell from the image is splitted and is stored in an array.
A trained CNN model on MNIST dataset is used to recognize the digits in the sudoko image.
The Extracted sudoko is solved .
