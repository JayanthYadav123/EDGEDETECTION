# EDGEDETECTION

## Aim:
To perform edge detection using Sobel, Laplacian, and Canny edge detectors.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
<br>

Import the required packages for further process.

### Step2:
<br>

Read the image and convert the rgb image to gray scale image.

### Step3:
<br>

Use filters for smoothing the image to reduce the noise.

### Step4:
<br>

Apply the respective filters - Sobel, Laplacian edge detector and Canny edge detector.

### Step5:
<br>

Display the filtered image using plot and imshow.

## Program:
```
DEVELOPED BY: G.Jayanth.
REGISTER NUMBER:212221230030
```
``` Python
# Import the packages
import cv2
import matplotlib.pyplot as plt
image = cv2.imread("dip2.png")
gray_image = cv2.cvtColor(image,cv2.COLOR_BGR2GRAY)
new_image = cv2.GaussianBlur(gray_image,(3,3),0)

# Load the image, Convert to grayscale and remove noise



# SOBEL EDGE DETECTOR



# LAPLACIAN EDGE DETECTOR



# CANNY EDGE DETECTOR




```
## Output:
### SOBEL EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>


### LAPLACIAN EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>


### CANNY EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>

## Result:
Thus the edges are detected using Sobel, Laplacian, and Canny edge detectors.
