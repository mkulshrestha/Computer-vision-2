# Computer-vision-2
Task 1 refers to using morphological operations to remove noise from the images. The basic operations that is erosion and
dilation are used to achieve opening and closing and then both opening followed by closing and vice versa are performed 
on the same image to note down the difference in the resulting images.

Task 2 is based on image segmentation and point detection. The image is convoluted with a 3x3 kernal and then a threshold 
is chosen to detect points of different intensities.

Task 3 is to detect horozontal and slanting lines using hough transformation. first we apply edge detection operators such as 
sobel or canny to obtaing the edges in the image. then we calculate rho and theta to populate accumulator matrix. then we 
select the rho and theta values more than the set threshold and plot the lines.
