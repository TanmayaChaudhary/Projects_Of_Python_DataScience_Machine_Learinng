# Road Line Detection

### In this project we detect the right & center white line on the road.

### First we access the camera of system & pass a video of running cars into it.

### Take frame one by one and apply the below processes.

### Processes ->
1-> Convert frame to gray format. 
2-> Apply Gaussian Blur to it.
3-> Apply Canny Edge Detection to find the edges in the frame.
4-> Apply Mask to the Canny Edge Detected Edge.
5-> Apply Hough Lines For detecting the coordinates of required lines.
6-> Then reshape the coordinates into 2D array ex-> (-1,4)
7-> Now draw the rectangle of red color on the Original Frame.

8-> Display the final image with the detected lines.
### Original Image
![Original](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/solidWhiteRight.jpg)

### Gray Image
![Gray](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Gray.png)
### Blur Image
![Blur](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_GBlur.png)
### Canny Edge Detection Image
![Canny](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_CannyEdge.png)

### Mask
![Mask](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Mask.png)

### Required Mask
![RequiredMask](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Mask_Required_Area.png)

### Hough Line Image
![Hough](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Hough_Line.png)

![Rectangle](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Final.png)
### Final Output
![FinalOut](https://raw.githubusercontent.com/TanmayaChaudhary/Projects_Of_Python_DataScience_Machine_Learinng/master/Road_Lane_Detection/Lane_Detection_Images/Line_Detection_Final.png)
