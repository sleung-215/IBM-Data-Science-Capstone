# IBM-Data-Science-Capstone
<i> This repository introduces the capstone project for IBM's Data Science Professional Certification. It will introduce a problem and apply location data and analysis methods to present a business solution. 

Folium maps are not displaying properly in Github. Please see pdf presenation.</i>

The following files for the Capstone are:
<ul>
   <li>Presentation (PPT): IBM Capstone-Chicago-Presentation.pdf</li>
   <li>Capstone Report (Document): IBM Capstone_Battle of the Neighborhoods-Chicago.pdf</li>
   <li>Jupyter Notebook (Code): IBM Capstone-Chicago.ipynb</li>
   </ul>


## <b> 1). Introduction to Business Problem </b>
Chicago is one of the most populous and growing US cities in the country. It is the home to plenty of arts, entertainment, sports, education, research and much more. No wonder Bean-town is attracting plenty of young professionals moving into the busy city each year. Chicago is a relatively young city with the person's average age being 34.9 years old and 63% of the population being single out of 2.7 million residents and growing.

With a growing city full of young people moving to Chicago looking for entertainment and adjusting to life in a new city, there has been demand on creating programs to research and provide information to those new to the city, create guides for tourists and keep the city's economy booming.

In this project, we will use location data and clustering techniques to determine which areas of Chicago has the most activity and human traffic. This can help a new city transplant select which is an accessible and quiet neighborhood to potentially select their new home.

## <b> 2). Data Sources: Downloading & Prepping Data </b>
The data sources used in this project consist of:
1. Wikipedia: List of Chicago neighborhood data

   https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Chicago

   This data source contains a list of the different neighborhoods in Chicago which will be utilized to cluster into larger sections of    the city to help populate different venues in the city. This will help cluster and determine the neighborhood with the most              activities and convenience in the city.

2. Foursquare API: Retrieved different venues in the different neighborhoods of Chicago
Foursquare API data will be used to determine the different venues located around the city. The different venues that will be obtained from location data will include restaurants,and entertainment (theaters, bars, gyms etc.).
Combining the neighborhood clusters and populating the different types of venues within each neighborhood will help determine which part of the city is will contain the necessities for daily life and entertainment with low human traffic within the area. 

3. Python packages used:
   <ul>
   <li>Pandas</li>
   <li>Folium Maps</li>
   <li>BeautifulSoup</li>
   <li>Geocoder</li>
   <li>Sklearn</li>
    </ul>

## <b> 3). Methodology </b>

<ul>
<li>Build a dataframe of neighborhoods in Chicago, IL by web scraping data from a Wikipedia page.</li>
<li>Get the geographical coordinates of the different neighborhoods.</li>
<li>Explore and cluster the neighborhoods to determine which neighborhoods are within city center.</li>
<li>Obtain the venue data for the cluster that contain city center neighborhoods from Foursquare API.</i>
<li>Determine the top 10 venues within each neighborhood and perform k-means clustering for each.</li>
<li>Select the best neighborhood in each cluster that contains the most venues.</li>
</ul>


<i>Census data reference: https://censusreporter.org/profiles/16000US1714000-chicago-il/ </i>
