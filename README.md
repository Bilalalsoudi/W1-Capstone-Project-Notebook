Capstone-Project-Notebook

Files 
1 - Segmenting and Clustering Neighborhoods in Toronto-Map ..displayong the map to show the Neighborhoods (Toronto based)

    This is to illustrate the MAP of toronto naigborhoods since GITHUB will not be able to render it. 

2-  Segmenting and Clustering Neighborhoods in Toronto.IPNYB (Python based coding)
 implemeting the following 
 
  Step 1 - Installation: We Install the required libs
  
    1 -Install geocoder.
    2-Install BeautifulSoup4.
    
   
   Step 2 - Scraping and creting data frame:
   
    a-Scrape Wikipedia page, https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M, in order to obtain the data that is in the table of # postal codes and to transform the data into a pandas dataframe
    b- Display data scraped from WIKI page.
    c-Exporting scraped data into Data Frame. The data frame will consist of three columns: PostalCode, Borough, and Neighborhood.  
     d-More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, you will notice that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11 in the above table.  
    e-Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned.  
    f-If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the borough.
   
  
  Step 3- Get the latitude and the longitude coordinates of each neighborhood and update the data frame to add two new columns for latitude and the longitude coordinates of each neighborhood
  
    a-Importing the csv file conatining the latitudes and longitudes for various neighbourhoods in Canada. 
    b-Merging the two tables for getting the Latitudes and Longitudes for various neighbourhoods in Canada.
  
  Step 4- Explore and cluster the neighborhoods in Toronto. You can decide to work with only boroughs that contain the word Toronto and then replicate the same analysis we did to the New York City data
  
    a-Map Toronoto based naigborhood (Visualize)
  
  
  
