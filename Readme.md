# Urban Geospatial Analytics with Foursquare & Open City Data

This repo contains a set of Jupyter notebooks that use geospatial data, the Foursquare Places API, and open city datasets to analyze how venues and infrastructure are distributed across NYC and Toronto neighborhoods.

The notebooks cover three related analyses:

1. **Manhattan Indian Restaurant Siting**
   - Use NYC neighborhood boundaries and Foursquare venue data to locate Indian restaurants across Manhattan.
   - Cluster neighborhoods based on venue composition to highlight saturated vs underserved areas for opening a new restaurant.

2. **NYC Hospital / Emergency Infrastructure vs COVID-19 Mortality**
   - Collect medical-related venues (hospitals, emergency rooms, urgent care, etc.) around NYC neighborhoods.
   - Join with borough-level COVID-19 deaths and population to compare healthcare access and deaths per 1,000 residents.
   - Cluster neighborhoods by their medical-venue mix to explore patterns in healthcare coverage.

3. **Toronto Postal-Code Neighborhoods (Wikipedia Scrape)**
   - Scrape the “List of postal codes of Canada: M” Wikipedia page.
   - Clean and aggregate postal codes, boroughs, and neighborhoods into a structured dataset for Toronto-based geospatial analysis.

## Tech stack

- Python, Jupyter Notebook  
- pandas, NumPy  
- Foursquare Places API  
- BeautifulSoup (HTML scraping)  
- scikit-learn (clustering)  
- Folium, geopy (basic mapping / geocoding)  
- Matplotlib (simple visualizations)

## How to use

1. Install dependencies in a virtualenv or conda env (pandas, numpy, scikit-learn, folium, geopy, requests, beautifulsoup4, matplotlib).
2. Add your Foursquare API credentials in the notebooks where indicated.
3. Open each notebook and run all cells to reproduce the analyses and maps.
