# Astroparticles Visualization

## First step


The first step in our data visualization was to get familiar with the data, a file called "muchosdatos.dat", and read it. The particular data structure was a comma-separated values with 8 columns and 999841 rows, which were read with pandas.

The data come from an astroparticle simulation. The number in the first column represent a specific particle:

1 = photon

2 = positron

3 = electron

5 = muon +

6 = muon –

The next columns carry the following information:

Column 2: Linear momentum on x in GeV/c

Column 3 : Linear momentum on y in GeV/c

Column 4 : Linear momentum on in GeV/c

Column 5 : Distance on x axis (Rx)

Column 6 : Distance on y axis (Ry)

Column 7 : Fligh time in nanoseconds

Column 8 : Total energy in GeV

## Second step

For the second step, we add a column based on the dataframe first column. In the new column we associated each number of the firts column with its corresponding particle name.

## Third Step

For the thirhd step, we resize the data to prevent big numbers.

## Fourth step

For the fourth step, we delimited the x-axis and y-axis length, because the extension of both axis does not allow to visualize data correctly.The new axis limits involve the 99.38% of all the data.

## Final step

Finally we plotted the data with matplotlib and got the following result:

![alt text](https://github.com/ricard1997/Astroparticle-visualization/blob/main/result.png)
