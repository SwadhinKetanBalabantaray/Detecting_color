# Detecting_color
Image/Video Input: Reads an image from a file or captures video from a camera.

Color Space Conversion: Converts the image from RGB (Red, Green, Blue) to HSV (Hue, Saturation, Value).  HSV is often preferred for color detection because it separates color information (hue) from brightness (value).

Define Color Range: Defines the lower and upper bounds of the target color in HSV values.  This range specifies the colors to be detected.

Create a Mask: Creates a binary mask by comparing each pixel's HSV value to the defined range. Pixels within the range are set to white (255), and those outside are set to black (0).

Apply the Mask: Applies the mask to the original image, highlighting the detected color and making other colors appear darker or black.

Display Results: Displays the original image, the HSV image (optional), and the masked image, showing the detected color.
