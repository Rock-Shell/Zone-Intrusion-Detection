# Zone-Intrusion-Detection

1.	Read the frames of the video
2.	Subtract the previous frame from the current frame
3.	 Convert the result to grayscale and apply preprocessing.
4.	Use contour detection to detect the changes
5.	To remove unnecessary noise we will leave the changes that have area < threshold(900 in this case)
6.	To detect the changes only in a certain area, draw a rectangle at the starting frame. Changes will be detected only in that region.

![frame.png](https://github.com/Rock-Shell/Zone-Intrusion-Detection/blob/main/1.png)

The red square is the region where the changes have to be detected, whereas green box indicate movement.
 
