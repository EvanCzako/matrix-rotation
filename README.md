# matrix-rotation

Simple rotation of matrices or greyscale images.

rotate_image_regrid rotates the image and resizes its dimensions as necessary to incorporate all of the original image into the rotated output.

rotate_image_no_regrid rotates the image but maintains its original dimensions, implying that some data may be cropped out. This function also contains code to ensure that the image remains properly centered despite discrepancies between the parities of the rotated image's dimensions and the input image's dimensions. Particularly useful for circular apertures.

Please see function descriptions for further details.

[![View Matrix and Image Rotation on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/72589-matrix-and-image-rotation)
