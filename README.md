Download link : https://programming.engineering/product/com-sgn-110-exercise-9/

COM-SGN.110 – EXERCISE 9
The tasks should be completed and presented to TA during the lab session. Do not forget to upload your solutions to Moodle! Questions about exercises should be addressed to the TA personally, through Moodle messages or via email, which can be found on the Moodle page of the course.

1. Histogram Equalization for Color Images

    Load the image fruits.jpg and apply MATLAB built-in histogram equalization independently on each of R, G, and B components. (histeq)

    Write a function intensityeq, which takes as an input a color image in RGB color space, converts it to HSV color space, applies histogram equalization on the value component and converts the image back to RGB color space. (rgb2hsv)

*Note: HSI and HSV are similar in purpose and properties. The conversion formulas from RGB to HSI and HSV are, however, slightly different. Although only HSI is covered in the lectures, we use HSV color space in this exercise since MATLAB has a built-in function for the conversion.

Further reading: https://www.vocal.com/video/rgb-and-hsvhsihsl-color-space-conversion/

    Load images fruits.jpg and festia.jpg and apply the procedures from both a) and b) on them. Show the results together in 2-by-3 subplot and explain the effects of processing.

2. Object Extraction

Figure 1: Qinghai lake (left) and the extraction example (right)

Load image lake.jpg and extract the biggest lake.

Hints:

    You may consider changing the color space

    You may need a thresholding operation

    Labeling the image regions may also be helpful

    Useful MATLAB commands: graythresh, im2bw, bwlabel

