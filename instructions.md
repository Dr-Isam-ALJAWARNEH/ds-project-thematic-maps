# instructions
## follow the following instructions
1. [ ] run the example starting code and familiarize yourself with some geosaptial processing techniques, including:
    - sampling
    - spatial join
    - geo-visualization

2. [ ] reference papers include:
    > [1. Large-Scale Outlier Detection for Low-Cost PM10 Sensors](https://ieeexplore.ieee.org/document/9288694) 

3. [ ] start by performing Exploratory Data Analytics (EDA) for the data
    > for example
        - historgrams to study the distribution of data (you have three sensors)
        - ```Kernel Density (univariate, aspatial)```
        - get insights from the following:
    - [02_geovisualization](https://darribas.org/gds_scipy16/ipynb_md/02_geovisualization.html)
    - [Exploratory Spatial Data Analysis (ESDA)](https://darribas.org/gds_scipy16/ipynb_md/04_esda.html)
    - [NYC Data](https://github.com/PacktPublishing/Geospatial-Data-Science-Quick-Start-Guide/blob/master/Chapter02/NYC%20Data.ipynb)
    - [Performing Spatial operations like a Pro](https://github.com/PacktPublishing/Geospatial-Data-Science-Quick-Start-Guide/blob/master/Chapter03/Chapter3.ipynb) such as ```Spatial join```

4. [ ] reference papers include:
    > [1. online spatial sampling](https://www.researchgate.net/profile/Isam-Al-Jawarneh/publication/339562314_Spatial-Aware_Approximate_Big_Data_Stream_Processing/links/5ff45764299bf14088708888/Spatial-Aware-Approximate-Big-Data-Stream-Processing.pdf) and
    > [2. AQP](https://www.mdpi.com/1999-5903/15/8/263)
    > [3. AQP](https://www.mdpi.com/1424-8220/21/12/4160)
In those papers, geohash encoding have been used for sampling, your task is to use ```Google's S2``` and ```Uber's H3``` for encoding, and build a sampler based on those and then generate thematic maps (e.g., choropleth or heatmaps), then compare the accuracy and time-based QoS constraints, and accuracy of maps using Root Mean Square Error (RMSE)!
5. [ ] search appropriate open source implementations for those algorithms in Python!, for example:
    > [S2 Python](https://pypi.org/project/s2/)
    > [s2 RegionCoverer](https://github.com/pantrif/s2-geojson)
    > [geojson to H3](https://github.com/uber/geojson2h3)
    > [H3 grid](https://geographicdata.science/book/data/h3_grid/build_sd_h3_grid.html)
    >[H3](https://h3geo.org/docs/api/regions/)
    >[H3-geojson](https://github.com/kapil-grv/H3-geojson)

also interesting:
- [How to create a Choropleth map using Uber H3, Plotly & Python](https://medium.com/analytics-vidhya/how-to-create-a-choropleth-map-using-uber-h3-plotly-python-458f51593548)

- [Uber H3 for Data Analysis with Python](https://towardsdatascience.com/uber-h3-for-data-analysis-with-python-1e54acdcc908)
    - 
***team***
- [Dr. Isam Al Jawarneh](https://isamaljawarneh.github.io/) (***supervisor***)
- [Aesheh Essa]()
- [Shaima Yousif]()
