# instructions
## follow the following instructions
-----------------------
<!-- Task 2 -->
# [ ] Task 2! 
# `Update: April 7, 2024`
### `N.B.` references are available in the end of this instruction file!
# `Required OPTIMIZATION ==> IMPORTANT!`
## `TODO:` 
- you need to perform stratified-like sampling using `H3` and `Google's S2` similar to what has bee done with the `geohash` as per the examples attached in the starting code and those dicussed in the class, then you need to generate choropleth maps from the `original` and `sample` data, then compare the maps using metrics such as RMSE, RMSD, MAE, MAPE, R-Square
  - to calculate any of these metrics to test the accuracy, you need to group data into two distributions, one for the original and one for the simplified, then calculate those metrics as distances between distributions.

  Here, I am coding an example for RMSE, MAPE, Pearson, KL Divergence and other metrics for the count and Top-N respectively. That is to say, how much is the difference in count of `taxi` trips between the original data and the sampled data for each neighborhood in New York City (NYC). attached example notebook titled `stratified_sampling_RMSE_mobility_NYC.ipynb` in the `code` folder.

  # `TODO:`
  - you need to apply the same methods for the distribution of the averages, by how much the distribution of averages across neighborhoods in city-wide diverge for the simplified version data as compared to the original data
  - You need to apply the same methods to data sampled using `H3` and Google's `S2`, similar to what has been done with the geohash in the attached example notebook titled `stratified_sampling_RMSE_mobility_NYC.ipynb`
  - You also need to measure `running time` for each method, comparing the times required to generate choropleth maps using a sample withdrawn by `geohash`, or `H3` or `Google's S2`, then you compare this running time with time required for generating map using original data `without sampling`. Capture sampling fraction in `x-axis` and `running time` in `seconds` in the `y-axis`. something similar to the following:
![running_time](https://github.com/Dr-Isam-ALJAWARNEH/ds-project-Stratified-based-Geospatial-Online-Sampling/assets/15251404/2ff067ea-75bf-4c99-b0c8-59595547d3e9)
-------------------------------------------------
<!-- Task 3 -->
# [ ] Task 3! 
  # `TODO:` next
- apply everything you have done (and you need to do in `task2`) to a second dataset, probably `NYC taxi mobility data`, that is [available online](https://github.com/IsamAljawarneh/datasets/tree/master/data), `nyc1.zip`. the target variable is `trip_distance`. You need to capture `accuracy` and `running time` as described previously.

--------------------------------------------
<!-- Task 4 -->
# [ ] Task 4!
## writing your paper
# `IMPortant` test with more than one data, add NYC taxi mobility data (for journal paper, you need tests on more than one data):
[available online](https://github.com/IsamAljawarneh/datasets/tree/master/data), `nyc1.zip`
- start writing your paper, either for conferences or journal. For journal, use the `applied sciences` template atatched in the `target-venue` folder titled `applsci-template.dot`.
1.  [ ] Include (cite appropriately) all of the following papers! reference papers include:
    # Category A : for sampling desing and Approximate Query Processing (AQP)
    > Spatial-aware approximate big data stream processing [^2] and
    > Polygon Simplification for the Efficient Approximate Analytics of Georeferenced Big Data [^3]
    > QoS-aware approximate query processing for smart cities spatial data streams. [^4]
    > Spatially representative online Big Data sampling for smart cities. [^5]
    # Category B: for spatial join procesing
    > SpatialSSJP: QoS-Aware Adaptive Approximate Stream-Static Spatial Join Processor [^6]
    > Efficient Integration of Heterogeneous Mobility-Pollution Big Data for Joint Analytics at Scale with QoS Guarantees [^7]
    > Efficiently integrating mobility and environment data for climate change analytics.[^8]
    > Efficient QoS-aware spatial join processing for scalable NoSQL storage frameworks. [^9]
    # Category C: clustering DBSCAN
    > Efficient spark-based framework for big geospatial data query processing and analysis [^10]
    [^2]: Al Jawarneh, I. M., Bellavista, P., Foschini, L., & Montanari, R. (2019, December). Spatial-aware approximate big data stream processing. In 2019 IEEE global communications conference (GLOBECOM) (pp. 1-6). IEEE. [available online](https://www.researchgate.net/profile/Isam-Al-Jawarneh/publication/339562314_Spatial-Aware_Approximate_Big_Data_Stream_Processing/links/5ff45764299bf14088708888/Spatial-Aware-Approximate-Big-Data-Stream-Processing.pdf)
    [^3]: Al Jawarneh, I. M., Foschini, L., & Bellavista, P. (2023). Polygon Simplification for the Efficient Approximate Analytics of Georeferenced Big Data. Sensors, 23(19), 8178.[available online](https://www.mdpi.com/1424-8220/23/19/8178)
    [^4]: Al Jawarneh, I. M., Bellavista, P., Corradi, A., Foschini, L., & Montanari, R. (2021). QoS-aware approximate query processing for smart cities spatial data streams. Sensors, 21(12), 4160. [available online](https://www.mdpi.com/1424-8220/21/12/4160)
    [^5]: Al Jawarneh, I. M., Bellavista, P., Corradi, A., Foschini, L., & Montanari, R. (2020, September). Spatially representative online Big Data sampling for smart cities. In 2020 IEEE 25th International Workshop on Computer Aided Modeling and Design of Communication Links and Networks (CAMAD) (pp. 1-6). IEEE.[presentation available online](https://isamaljawarneh.github.io/talks/CAMAD20.pdf)
    [^6]: Al Jawarneh, I. M., Bellavista, P., Corradi, A., Foschini, L., & Montanari, R. (2023). SpatialSSJP: QoS-Aware Adaptive Approximate Stream-Static Spatial Join Processor. IEEE Transactions on Parallel and Distributed Systems. [available online](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10309986)
    [^7]: Al Jawarneh, I. M., Foschini, L., & Bellavista, P. (2023). Efficient Integration of Heterogeneous Mobility-Pollution Big Data for Joint Analytics at Scale with QoS Guarantees. Future Internet, 15(8), 263. [available online](https://www.mdpi.com/1999-5903/15/8/263)
    [^8]:Al Jawarneh, I. M., Bellavista, P., Corradi, A., Foschini, L., & Montanari, R. (2021, October). Efficiently integrating mobility and environment data for climate change analytics. In 2021 IEEE 26th International Workshop on Computer Aided Modeling and Design of Communication Links and Networks (CAMAD) (pp. 1-5). IEEE.[presentation available online](https://isamaljawarneh.github.io/talks/CAMAD21.pdf)
    [^9]:Al Jawarneh, I. M., Bellavista, P., Corradi, A., Foschini, L., & Montanari, R. (2020). Efficient QoS-aware spatial join processing for scalable NoSQL storage frameworks. IEEE Transactions on Network and Service Management, 18(2), 2437-2449.[available online](https://isamaljawarneh.github.io/pubs/TNSM3034150.pdf)
    [^10]: Aljawarneh, I. M., Bellavista, P., Corradi, A., Montanari, R., Foschini, L., & Zanotti, A. (2017, July). Efficient spark-based framework for big geospatial data query processing and analysis. In 2017 IEEE symposium on computers and communications (ISCC) (pp. 851-856). IEEE. [available online](https://www.academia.edu/download/55478212/08024633.pdf)
----------------------------------------------
<!-- Task 1 -->
# [ ] Task 1!  `partially completed!`
1. [X] run the example starting code and familiarize yourself with some geosaptial processing techniques, including:
    - sampling
    - spatial join
    - geo-visualization

2. [ ] reference papers include:
    > [1. Large-Scale Outlier Detection for Low-Cost PM10 Sensors](https://ieeexplore.ieee.org/document/9288694) 

# `this is partially completed! You need to complete it!, where is your Exploratory Data Analytics (EDA) and ESDA?!!!`
3. [ ] start by performing Exploratory Data Analytics (EDA) for the data
    > for example
        - historgrams to study the distribution of data (you have three sensors)
        - ```Kernel Density (univariate, aspatial)```
        - get insights from the following:
    - [02_geovisualization](https://darribas.org/gds_scipy16/ipynb_md/02_geovisualization.html)
    - [Exploratory Spatial Data Analysis (ESDA)](https://darribas.org/gds_scipy16/ipynb_md/04_esda.html)
    - [NYC Data](https://github.com/PacktPublishing/Geospatial-Data-Science-Quick-Start-Guide/blob/master/Chapter02/NYC%20Data.ipynb)
    - [Performing Spatial operations like a Pro](https://github.com/PacktPublishing/Geospatial-Data-Science-Quick-Start-Guide/blob/master/Chapter03/Chapter3.ipynb) such as ```Spatial join```
# `this is partially completed! You need to complete it!, where is your Google's S2 implementation and RMSE calculations?!!!`
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
