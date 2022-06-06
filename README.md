# Currency-Recognition-System-Using-Matlab
Introduction:
1) It is difficult for people to recognize currencies from different countries. For solving this problem, however currency recognition system that are based on image analysis entirely are not sufficient.
2) Currency Recognition system is implemented for automated currency recognition using image processing techniques. It is used in many scenarios such as bank, business firms, shopping malls etc.
3) The aim of ours system is to help people who need to recognize different currencies and work with convenience and efficiency. 

Objectives:
1) To reduce the human efforts to recognize different currencies.
2) To learn different image processing techniques. 
3) To implement automated currency recognition system using image processing.

Flow Chart:

![image](https://user-images.githubusercontent.com/66591733/172206939-ef411292-1d9e-493d-9bdf-1d9fe7233162.png)

Image Preprocessing:
1) RGB to Gray Scale Conversion: 
Grayscale is a range of gray shades from white to black, as used in a monochrome display or printout. Grayscale images are most commonly used in image processing because smaller data enables developers to do more complex operations in a shorter time.

2) Median Filtering:
Median filtering is a nonlinear process useful in reducing impulsive, or salt-and-pepper noise. It is also useful in preserving edges in an image while reducing random noise.

Feature Extraction:
1) Edge Detection: 
Edge detection is an image processing technique for finding the boundaries of objects within images. We used the following operators for edge detection:
	->Prewitt operator
	->Canny operator

2) Euler Number Calculation:
The Euler number (also known as the Euler characteristic) is the total number of objects in the image minus the total number of holes in those objects.

Output:
If the calculated value of the input image matches with the dataset, it will return the currency name and country name as follows. 
![image](https://user-images.githubusercontent.com/66591733/172207796-b62de8e8-9faf-4e28-a596-96619afeea9e.png)
