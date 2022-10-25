# A-Novel-Machine-Learning-Approach-to-Thyroid-Ultrasound-Segmentation
**Dissertation Code Repository**

**Data_Table_Complete_CSV_CLEAN.csv:** 

Contains seperate data for Height, Depth and Width for each axis in the scan


**Data_Table_Complete_FULL_CSV_CLEAN.csv:**

Data from **Data_Table_Complete_CSV_CLEAN.csv** is combined together into a two column dataset.


**Using_Polynomial_Regression_Getting_Values.ipynb:**

Code applies Polynomial Regression to values in **Data_Table_Complete_CSV_CLEAN.csv** and **Data_Table_Complete_FULL_CSV_CLEAN.csv** and using these values predict fixed mm per layer. This is the MAIN Code for Method 1.


**Using_Difference_Images_To_Predict_Error_With_3D.ipynb:**

Combination of **Using_Difference_Images_To_Predict_Error.ipynb:** and **Plotting_3D_Model.ipynb:**. This is the MAIN Code for Method 2

**Official_Image_Comparison_Multiple.ipynb:** 

Code finds the Absolute Error between Images passed to it. It loop through all the scans and finds the difference values and resulting Images. The resulting Images and Errors are saved to be used for the CNN.

**Error_Per_Diff_Image.xls:**

This is the data output from **Official_Image_Comparison_Multiple.ipynb:** It contains the errors between each Image in each Scan.

**Official_Image_Comparison.ipynb:** 

Practice Comparison Code.

**Official_Rescaling Images.ipynb:**

Code rescales images for the CNN Model so it can plot to scale.

**Percentage_Of_Total_Error_Diff_Image_Updated .xls:**

Data table based apon **Error_Per_Diff_Image.xls:** where each Error value was converted to a percentage.

**Plotting_3D_Model.ipynb:**
Code contains Pypotree which is used to plot for Method 2

**Using_Difference_Images_To_Predict_Error.ipynb:**

Code contains the CNN running prediction on Diff_Images.





