# Clustering London Neighbourhoods


![Contributors](https://img.shields.io/github/contributors/walidsi/analyze-AB-test-result?style=plastic)
![Forks](https://img.shields.io/github/forks/walidsi/analyze-AB-test-result)
![Downloads](https://img.shields.io/github/downloads/walidsi/analyze-AB-test-result/total)
![Stars](https://img.shields.io/github/stars/walidsi/analyze-AB-test-result)
![Licence](https://img.shields.io/github/license/walidsi/analyze-AB-test-result)
![Issues](https://img.shields.io/github/issues/walidsi/analyze-AB-test-result)


### Goal
London is a big European city with hundreds of venues spread all over its many neighborhoods. 
Our client is planning to open a restaurant / franchise in London and is seeking our advice to help them identify suitable location(s) where they can establish their business in the busy and condensed city of London, UK.
Competition is hard in the hospitality sector, so identifying locations that provide an opportunity for a profitable business and where there is real customer need is paramount.
Our analysis will aim to help them with this decision.

### Dataset
The data used for our analysis was obtained from two main sources:
- The first one is London, UK e-gov data store website at the following link: London Borough Profiles and Atlas - London Datastore.  This data includes the list of London 33 boroughs (including City of London borough). The names of London boroughs were supplemented with the co-ordinates for each borough. The latitude and longitude information for each borough were obtained by querying the Geopy library and appended to the list of London boroughs.
- The second source of information and data is the Foursquare.com location data database. This online database was used to obtain a list of 100 popular venues within 1000 meters from the center of each borough. This data is available publicly via Foursquare API calls. The location data for a venue includes venue name, latitude, longitude and category.
 

### Process
Our analysis centered on clustering the neighborhoods of London in order to find groups of similar neighborhoods, discover characteristics and obtain insights about each cluster of neighborhoods that will guide our recommendation for the best neighborhoods to open a new restaurant in London.

### Summary of Findings
Our analysis reveals the following findings:
- Brent borough is very similar to the heart of the city although it is away from the 4 main boroughs at the center of London. The 4 main boroughs are known for pubs, coffee shops and modern restaurants. Brent is considered similar to them but has fewer restaurants so an opportunity might be there to fulfill a need.
- Barking and Dagenham share the same cluster with Harrow, Hillingdon and Hounslow.  These 3 boroughs are popular in Asian restaurants, namely Chinese and Indian which are the most popular spots. Barking and Dagenham has Chinese and Turkish restaurants but not Indian so an Indian restaurant could be an option. 
- Similarly Newham is in the same cluster with Harrow, Hillingdon and Hounslow. Newham is known for Fish and Chips. An opportunity could be there for an Asian cuisine.
- The 22 boroughs a around the center of London are jam-packed with pubs and restaurants of all cuisines. It will be very competitive to consider establishing a restaurant business there.
- The results section revealed interesting findings of the clustering algorithm. Brent, Barking and Dagenham and Newham are suggested boroughs for a promising restaurant franchise. The analysis narrowed the initial 33 boroughs to just 3. Further field analysis is required in these boroughs to confirm the findings on the ground.

### Install
This project requires **Python 3.x** and the following Python libraries installed:
- [NumPy](http://www.numpy.org)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org)
- [statsmodels](https://www.statsmodels.org)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code
Code is provided in the `***.ipynb` notebook file.

### Run
In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook **.ipynb
```  
or
```bash
jupyter notebook **.ipynb
```

This will open the iPython Notebook software and project file in your browser.


