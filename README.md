### Launch using: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/annabednarska/Vertical-Jump-Test/HEAD?urlpath=voila%2Frender%2Fvertical-jump-test.ipynb) 
<sup>(please be patient, server needs few minutes to start)</sup>


### ABOUT

In this app you can perform force-time analysis for two trials of vertical jumps (squat jump or counter movement jump) for groups of athletes. 

The goal is to speed up the (manual) process of analyzing outputs from contact platforms and provide an automatic solution: to cut the data, normalize time, generate plots for each group and make statistical test.

#### How does it work? 

1. Uploaded data are prepared for analysis. For each jump, the app removes parts of the athlete standing still on the platform (before and after performing the test) to keep only essential jump information. 
2. Time is normalized to percentage values. 
3. Plots for each group and try are generated.
4. Statistical Parametric Mapping is performed for 0.05 significance level using parametric or nonparametric test, depending on prior normality check. 

### HOW TO RUN THE TEST

Sample files are available in _test_files_ folder.


1. In Select jump type field choose jump type which you want to test (Squat jump or Counter movement jump)
2. In Upload files for first trial, select from your drive .xlsx files with data for entire group performing first trial. Click 'OK' button.
3. In Upload files for second trial, select from your drive .xlsx files with data for entire group performing second trial. Click 'OK' button.
4. Click 'RUN TEST' to see the results of SPM test - plots and intervals where differences occurred. IMPORTANT! Minimum size of each group to perform the test is 2.

---

If you run into problems, have questions or ideas for improvements / additional features, feel free to contact me: anna.b.bednarska@gmail.com

Test designed in cooperation with [Amit Batra](https://amitbatra.pl/) 
