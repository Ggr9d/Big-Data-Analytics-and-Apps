# ICP-4

#### Complete the following:
```
Name: Karthik Yanagandula
Email: kyb8k@umsystem.edu
```
---
```
Partner Name: Vinay Reddy Kalluri
Partner  Email: vk9ry@umsystem.edu
Partner ICP-Link: https://github.com/UMKC-APL-PythonDeepLearing/icp_4-vnreddy60

```
### SUBMIT PYTHON NOTEBOOK FILE (ipynb file):

```
Video Link: https://www.youtube.com/watch?v=1LEzZyBeIYs
```
<br/>
 
Write a brief explanation here:

1. Operations on the array using NumPy library
	* Imported the necessary library for Numpy operations using import NumPy.
	* An array of random size 15 with range 1-20 created using random randint. 
	* An array of size 15 is printed.
	* Array changed to size 3*5 using reshape.
	* Using apply along the axis from NumPy to find the max along the axis using max function. The highest value got replaced by '0'.
	* Possible diagonal extracted the updated matrix.
	* Updated matrix data got updated to output.npy file and loaded the data to print again from the file to check the data from the same file.

2. Operations on CSV File using Pandas Library
	* Imported the necessary library for Pandas operations using import pandas.
	* CSV file loaded to pandas using read_csv.
	* Basic statistics like data types, column details, axes, dimensions, size, and shape of the data printed using pandas.
	* data loaded in data frame object, checked for values to contain any nulls and status returned as True.
	* Identified the column which is having null values and replaced them with mean using fillna and inplace.
	* Merged Pulse and Calories and data fetched using min, max, count, and mean.
	* Using greater than and less than operator calories details adjusted in the data frame.
	* Using greater than and less than operator calories and pulse details adjusted in the data frame.
	* Modified the data frame to have only duration, pulse, and calories.
	* Using del function max pulse column deleted from the data frame.
	* Using astype method float converted to int.
	* Scatter plot between duration and calories using the matplotlib library.

3. Operations on Image using the matplotlib library
	* Imported the necessary library for matplotliboperations using import matplotlib.
	* Using imread image is loaded into local.
	* Fetched the image size.
	* cropped the image based on the available shape to get the required one.
	* Saved the image to cropped_image.
	* Using npwhere image with less than 200 pixels changed to black by replacing it.
	* print the formated image.
    * Saved the image to np_where_image.