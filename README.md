[Readme.txt](https://github.com/user-attachments/files/26862916/Readme.txt)
Order:


thermocouple data is used to calibrate the IR intensity

1. time_average_std_calculation to calculate the mean of temperature for each thermocouple.

2. Time_average_calculation (under the infared_data) folder to calculate the time average of intensity map.  

3.  unsuccessful_average_detection : detect which folder may not contain files to calculate the average

4.  average_intensity_plot : plot the IR intensity for all the cases

5. Correction_Application: extract the window and apply corrections to the 1st window

6. Rename_corrected_file: rename the saved file to the first correction window

7. Correction_Application: extract the window and apply corrections to the second window

8. Rename_corrected_file: rename the saved file to the second correction window

9. interpolation: to standardize the size of all the field: to 150 * 150 

10. infrared_intensity_extractor : extract points corresponds to thermocouple to do the calibration

11. linear_regression:  point mapping and linear regression

12. temperature_calc_based_on_regression: calculate the temperature to obtain the map

13. upper_half_cropping: remove the lower part of the image and keep only the upper half.

14. temperature_inpainting_1st_action: remove the thermocouple stains

15. temperature_inpainting_2nd_action_correc: remove the effusion holes stains

16. spanwise_avg_std_compound_angle: calculate the spanwise average and standard deviation

17. pixel_calibration_streamwiseOrdering.ipynb:  combine data and reorder in streamwise direction

18. 
