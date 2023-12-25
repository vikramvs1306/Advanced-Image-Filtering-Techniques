Project Name: Image Filtering and Enhancement

Input Image:
You will be working with Lenna's picture. Please convert it to .png format before using it.
Download the image from the following link:
https://eeweb.engineering.nyu.edu/~yao/EL5123/image/lena_gray.bmp

Project Description:
This project involves implementing various image filtering techniques to enhance and manipulate an input image. The goal is to apply different filters to the image, save the filtered images, compute the differences between the input and filtered images, and normalize the resulting pixel values.

Program Structure:
- The main program reads an input image from a file named "filename."
- If the image is in RGB format, it is converted to a grayscale image.
- Four different filters are applied to the grayscale image:
    1. 3x3 w-filter
    2. 3x3 Laplacian filter with +8 at the center
    3. Unsharp masking using a 5x5 Gaussian filter with σ^2 = 100
    4. 3x3 averaging filter followed by a 3x3 Laplacian filter with -4 at the center.

Filtering Steps:
1. Apply the filter to the grayscale image.
2. Save the filtered image in a file named "filenameFilterType."
3. Compute the difference between the input and filtered images.
4. Normalize the resulting pixel values to the range [0, 255].
5. Save the normalized difference image in a file named "filenameFilterTypeDiff."


