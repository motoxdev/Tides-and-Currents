# Tides-and-Currents
# Devyn Holland 
# CS 510

PURPOSE:
The purpose of this project is to read in the 'tide and current' excel spreadsheet and produce the most common frequencies.

FILE EXPLANATIONS: <br />
fourierTides.csv - data file <br />
README.md - Comments/Documentation of project <br />
Tides and Currents.Rmd - code <br />
Tides and Currents.Rproj - entire project <br />


CODE ORGANIZATION/PROCESS:
-The fourierTides.csv file contains tide and current data from 8/1/2020 to 7/31/2021. This data will be read into RStudio.
-First, mathematical calculations will be produced as variables (The function 'fft(x)' will be utilized to conduct the Fourier Series analysis on the data set).
-Second, a harmonics plot will be created to show the all the values provided within fourierTides.csv.
-Third, will set up 2 more plots: one for frequencies per month and one for frequencies per day.
-Fourth, calculate the amplitude and frequency, then compare those two variables to one another on another plot.
-Fifth, sort the points of the Amplitude VS Frequency plot, and select the top 15 in amplitude
-Sixth, convert these units into frequencies, and you produce top 15 frequencies of the data set.
