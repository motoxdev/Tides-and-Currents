# Tides-and-Currents
Devyn Holland <br />
CS 510

**PURPOSE:** <br />
The purpose of this project is to read in the 'tide and current'
excel spreadsheet and produce the most common frequencies.<br />

**FILE EXPLANATIONS:** <br />
* fourierTides.csv - data file <br />
* README.md - Comments/Documentation of project <br />
* Tides and Currents.Rmd - code <br />
* Tides and Currents.Rproj - entire project <br />


**CODE ORGANIZATION/PROCESS:**<br />
1. The fourierTides.csv file contains tide and water level data from 8/1/2020 to 7/31/2021. Make sure this file is downloaded in order to be read into RStudio.<br />
2. Mathematical calculations will be created as variables (The function 'fft(x)' will be utilized to conduct the Fourier Series analysis on the data set).<br />
3. A harmonics plot will be created to show the all the values provided within fourierTides.csv.<br />
4. Set up 2 more plots: one for frequencies per month and one for frequencies per day.<br />
5. Calculate the amplitude and frequency, then compare those two variables to one another on another plot.<br />
6. Sort the points of the Amplitude VS Frequency plot, and select the top 15 in amplitude. <br />
7. Convert these units into frequencies, and you produce top 15 frequencies of the data set. <br />
