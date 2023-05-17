## Ex no: 10
# <p align="center">Implementation of Erosion and Dilation

## Aim
To implement Erosion and Dilation using Python and OpenCV.
## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step1:
<br>Import the necessary packages.


### Step2:
<br>Create the Text using cv2.putText.

### Step3:
<br>Create the structuring element.

### Step4:
<br>Erode and Dilate the image.

### Step5:
<br>End Program.

 
## Program:
```
DEVELOPED BY : Arun kumar R
REG NO :212220233001
```

``` Python
# Import the necessary packages

import cv2
import numpy as np
import matplotlib.pyplot as plt



# Create the Text using cv2.putText
img1 = np.zeros((100,270), dtype = 'uint8')
font = cv2.FONT_HERSHEY_SIMPLEX
cv2.putText(img1,'aakaash',(5,70), font, 2,(255),5,cv2.LINE_AA)
plt.imshow(img1,'gray')


# Create the structuring element
cv2.erode(img1, kernel)
kernel = cv2.getStructuringElement(cv2.MORPH_CROSS,(7,7))




# Erode the image

image_erode1 = cv2.erode(img1,kernel)
plt.imshow(image_erode1, 'gray')



# Dilate the image

image_dilate1 = cv2.dilate(img1, kernel)
plt.imshow(image_dilate1, 'gray')



```
## Output:

### Display the input Image
<br>![download](https://user-images.githubusercontent.com/70016683/235285567-67d80848-c7dc-42b5-852f-e8f62f77cd52.png)


<br>
<br>
<br>
<br>
<br>

### Display the Eroded Image
<br>![download (1)](https://user-images.githubusercontent.com/70016683/235285579-ea996e26-426a-4ecf-8ad0-38396abfb8b0.png)


<br>
<br>
<br>
<br>
<br>

### Display the Dilated Image
<br>![download (2)](https://user-images.githubusercontent.com/70016683/235285598-117573ef-bbae-4ab0-a51a-98c5fd3473bf.png)


<br>
<br>
<br>
<br>
<br>
<br>

## Result
Thus the generated text image is eroded and dilated using python and OpenCV.
