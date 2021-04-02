# Creation-of-Matrix-using-numpy
Creation of Matrix of size 3*3 using numpy library

import numpy  # Importing the numpy library
num=input()   # Created a varialbe 'num' to take the input of numbers 
l=[int(i) for i in num.split(' ')]  # Splitting the  numbers taken by 'num' with space and saved into the list 'l'
Mat= numpy.array(l) # Passing the list of values in the list 'l' into the variable "Mat"
Mat.shape=(3,3)   # Assigning the shape to the matrix 'Mat'
print(Mat)        # Printing the output of the variable 'Mat'
