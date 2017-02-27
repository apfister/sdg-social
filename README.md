SDG Live
=======================

This app is a customized version of the Live Maps ArcGIS Online template. Live Maps is a configurable template for providing live feeds within the map's initial extent.

[View it live](http://sdg.esri.com/social/)

[View the Live Maps template live](http://coolmaps.esri.com/templates/LiveMapsFood/)
Read more about the Live Maps template [here](https://github.com/SpatialAgent/live-maps)

#Features

- Every time you load the app, it’ll pick a random goal to show
  - You can directly link to a goal using a URL like this, `http://sdg.esri.com/social/?sdg=2`, changing the “sdg” parameter
- Use the map to zoom in and out to show tweets around that location
- Click the rotating SDG Logo at the top, then click any of the goals to set it to show tweets on the map
- Use the search box in the upper right to change the search keywords that you send to the twitter API
  - Some examples of searching
    - SDG2
    - SDG2 OR “hunger”
      - Will return tweets including SDG2 or exactly hunger (using quotes around hunger)
    - #SDG2 AND zero hunger
      - Will return tweets that include hashtag SDG2 and the keywords zero, hunger

#Instructions

1. Download and unzip the .zip file or clone the repo.
2. Web-enable the directory
3. Access the .html page
4. See the Live Maps [README](https://github.com/apfister/sdg-social/blob/master/README.md) page for more details.
