# FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python
Introduction to how to use MATLAB to design FIR and IIR filters and apply into your python program. 



## Instruction about generating filter by MATLAB:
Calling the filterDesigner in the MATLAB:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/first_step.jpg)


Using the filterDesigner to design the filter we needed by setting the parameters such as response type, design method, filter order, frequency specifications and so on:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/filter_designer.jpg)


Generating a FIR filter by using filterDesigner and export the coefficients:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/pic/export.jpg)


Showing the coefficient in the command window:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/pic/Num.jpg)


Generating a IIR filter by using filterDesigner and export the coefficients:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/pic/IIR_filter.jpg)


Transferring the SOS and G into the b and a coefficents:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/pic/ba_coefficients.jpg)


After getting the coeffients, we can copy them into the python program to implement the filters.
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/blob/main/pic/pic/coefficients_copy.jpg)
