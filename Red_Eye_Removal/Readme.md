# Red Eye Removal

### In this project we remove the red colored images from a red eye image.

### So first we take a red colored image form the system or any where esle.

### Then apply some process to it :->

### 1-> Convert it to graycolor.
### 2-> Build a eye detector for detecing the eyes.
### 3-> Now Detect the eyes from the image.
### 4-> Now crop all the images of the eyes.
### 5-> Now take one eye image & split it into the RGB format.
### 6-> Then apply Thresholding to all the 3 RGB color format splitted images.
### 7-> Now combine red image with the combination of blue & green image.
### 8-> Now fill the center Dot of the image because it is the red portion.
### 9-> Make a mask of it.
### 10-> Now apply the whole process to all the images.

### SO finally we removed the red eyes.

### Red Eyes
![RedEyes](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Red_Eye_Removal/Red_Eye_Images/RedEye.jpg)

### Final Output after removal of Red Eye
![RedEyesRemoval](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Red_Eye_Removal/Red_Eye_Images/Red_Eye_Removal.png)
