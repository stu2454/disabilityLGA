# disabilityLGA
an attempt to plot NDIS recipients by LGA

I wrote this code to see if I could plot the number of participants in the NDIS across different LGAs.

Found LGA data on the ABS site: https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files

And disability data at the NDIS site: https://data.ndis.gov.au/datasets/participant-datasets

Had to muck around a bit getting link between LGA names in the the shapefile and the excel file. LGA from ABS were from 2020 while LGAs in NDIS data are 2023. Also had to spend a bit of time cleaning the names given the different conventions in LGA names between the two files.

eveythung coded in python in a Jupyter Labs notebook
