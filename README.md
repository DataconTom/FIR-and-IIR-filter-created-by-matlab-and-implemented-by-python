# FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python
Introduction to how to use MATLAB to design FIR and IIR filters and apply into your python program. 



## Instruction about generating filter by MATLAB:
Calling the filterDesigner in the MATLAB:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/tree/main/pic/first_step.jpg)
Using the filterDesigner to design the filter we needed by setting the parameters such as response type, design method, filter order, frequency specifications and so on:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/tree/main/pic/filter_designer.jpg)
Generating a FIR filter by using filterDesigner and export the coefficients:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/pic/export.png)
Showing the coefficient in the command window:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/pic/Num.png)
Generating a IIR filter by using filterDesigner and export the coefficients:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/pic/IIR_filter.png)
Transferring the SOS and G into the b and a coefficents:
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/pic/ba_coefficients.png)
After getting the coeffients, we can copy them into the python program to implement the filters.
![image](https://github.com/DataconTom/FIR-and-IIR-filter-created-by-matlab-and-implemented-by-python/pic/coefficients_copy.png)
