Dataset will be separate into 3 parts.

1. Raw dataset use for cleaning (Jupyter notebook)
   1. Due to the file size, We can only upload 1 city's (Amsterdam) raw data here. (You can download the rest of the cities from the site below)
   2. We will need the listings.csv & reviews.csv (I have shorten the reviews.csv to 60,000 rows, too big to be uploaded to github)
   3. Website: http://insideairbnb.com/get-the-data/
   4. After cleaned, it will output as 2 files: atd_list.csv & p_atd_rev.csv
      
2. Data for loading to SQL (Jupyter notebook + PgAdmin4)
   1. After the data is cleaned, it will be loaded into the code.
   2. We will need atd_list.csv & p_atd_rev.csv (We can do the same for the other cities as well)
      
3. Data for Sentimental Analysis (Jupyter notebook)
   1. We will need connection to PgAdmin in order to run the analysis.
   2. Alternately, you can use atd_list.csv & p_atd_rev.csv to run as well (With a few adjustment in the codes)
