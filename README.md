## NASA-Meteorites-Analyses

I was interested in exploring Meteorite Landings Data from NASA, Data.Gov. to examine how many meteorites were landed on earth.

### Research Questions to Answer:
1) How many meteorites were found? 
2) Which meteorites were found in the earliest year?
3) What sizes of meteorites were found so far? 
4) Where were the largest meteorites’ landing spots?
5) What types of meteorites did we find?
6) Which countries found more meteorites?

### Materials & Methods
1) I obtained the csv file from Data.gov - the total rows were 45,716. The last update was conducted on July 17, 2020.
2) I used: python - pandas (data manipulation), citipy (for obtaining city and country names to match with geo locations), and matplotlib and gmap (for visualization).
3) Data manipulation: I removed date and time from a column of 'year' by splitting the column information. I obtained city and country names for each data row using 'citipy' by using GeoLocation.

![citipy](ReadMe_Images/citipy.png)


### Results
1) How many meteorites were found? - There were 706, 24,004, and 13,404 meteorites discovered on earth < 1900, 1900-2000, and 2000-current year, respectively.

![total_number](ReadMe_Images/Total_Number_Meteorite_Years.png)

* I set up bins to create a range of years to show the total number of meteorites for each year range.
  
![total_number](ReadMe_Images/Total_Number_Meteorite_YearRange.png)


2) Which meteorites were found in the earliest year? - The oldest meteorite found on earth was Nogata city in Japan in 860.
![table](ReadMe_Images/table_1.png)

![map_1](ReadMe_Images/oldest_meteorites.png)


3) What sizes of meteorites were found so far? 


