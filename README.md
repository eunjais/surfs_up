# SURFS UP

This Surfs Up analysis gathers temperature and precipitation data for the months of June and December in Oahu, in order to determine whether the surf & ice-cream shope business, should it open, can be sustainable year round.

## Programs Used
- Python
- Pandas
- SQLAlchemy
- SQLite
- Matplotlib
- Jupyter Notebook 
- VS Code

## Analysis

### Overview - Deliverable 1 

Deliverable 1 utilizes Python, Pandas and SQLAlchemy to filter the dates of hawaii.sqlite and retrieve temperatures for June. Consecutively, these temperatures are analyzed for a better understanding of the temperature range, et cetera. 1700 total data points showed the following:

![june](https://user-images.githubusercontent.com/107447038/185812685-b7054662-a8d3-40b5-a349-dab9c3d236da.png)

The mean temperature of June is 74.9 F, with the minimum at 64 F and maximum at 85 F.


### Overview - Deliverable 2

Similarly, Deliverable 2 retrieves the temperatures in Hawaii for the month of December. 

![december](https://user-images.githubusercontent.com/107447038/185812750-15e79136-373d-499a-9c51-72d6571d4906.png)

The mean temperature of December is 71 F, with a minimum at 56 F and maximum at 83 F.

### Results - June VS December

- June had an average temperature higher than December by 4 F. 
- The standard deviation between these average temperatures were lower in June compared to December, meaning June had a more stable range of temperatures. 
- June also had a higher minimum as well as maximum temperature compared to December, at 64 F (as opposed to 56 F) and 85 F (as opposed to 83 F), respectively.

June Plot:

![juneplot](https://user-images.githubusercontent.com/107447038/185812718-53177084-d716-4b61-8914-ef6b9011e1b4.png)

December Plot:

![decplot](https://user-images.githubusercontent.com/107447038/185812776-e50ebf4b-9312-4836-bc04-d9dcae71fe5f.png)

### Summary and two additional queries

We wanted to see how preicipitation amounts compare between the two months, June and December.

June Precipitation:

![june_precipitation](https://user-images.githubusercontent.com/107447038/185817134-20794334-02f9-4aa7-aaed-1a7d5ad0f7ab.png)

June has an average precipitation of 0.14 mm, with minimum being no daily rain and maximum being 4.43 mm.

December Precipitation:

![dec_precipitation](https://user-images.githubusercontent.com/107447038/185817140-2e9d0bdc-1e6a-4388-b3f6-54330868bf34.png)

December has an average precipitation of 0.22 mm, with minimum being no daily rain and maximum being 6.42 mm. 

From this, we can conclude that while there is a subtle increase of precipitation between June and December, the difference is negligible ( 0.6 mm) This likely reflects the weather and climate trend of the area; Hawaii's wettest months are known to be from November to March, but heavily localized weather makes it so that it isn't overwhelming. 

Conclusively, we see there's negligible amount of difference, temperature-wise and precipitation-wise, between the months. The lowest temperatures in December may pose a decrease of customer population since 56 F is quite chilly, but the average days show promise.
