# ELECENG-712
Digital Imaging - Project 1

Asked to re-sample a 2D digital image: Specifically, you are asked to re-sample an input 
image by t times in both x-axis and y-axis, where t is an arbitrary positive float-type 
scale factor. Please consider bi-linear (BL) interpolation at (x, y) in case x or y is 
not at a grid point (or integer).

Hint: Assume the input image has a size of M * N. First you need to determine the size of
the output image by multiplying both M and N by t. That is, M' = M * t and N' = N * t.

Submit: 
  
  a.) source code
  
  b.) Two output images in PGM format or others (BMP, JPG, etc.)
  
      i.)   one for downsampling (t < 1) 
      ii.)  one for up-sampling (t > 1)
      
